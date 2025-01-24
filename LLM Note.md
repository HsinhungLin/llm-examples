# 模型微調
## Ollama 使用自己的模型
[參考](https://hackmd.io/@flagmaker/HkQHhlYyA)
1. 從Huggingface 下載gguf模型 放到下載的目錄中
	https://huggingface.co/QuantFactory/Llama-3.2-3B-GGUF?show_file_info=Llama-3.2-3B.Q8_0.gguf
2. 使用ollama 建立模型
	a. 建立Modelfile.txt 放到user目錄中
	Modelfile.txt的內容
	FROM ./downloads/mistrallite.Q4_K_M.gguf
	b. 執行指令
	ollama create 自訂模型名稱 -f Modelfile.txt
3. 檢查模型是否建立
    Ollama list
4. 運行模型
    Ollama run 自訂模型名稱
    
## 免費開源 AI 助手 Ollama 從安裝到微調
[離線不怕隱私外洩！免費開源 AI 助手 Ollama 從安裝到微調，一支影片通通搞定！](https://www.youtube.com/watch?v=JpQC0W91E6k&list=WL&index=8&t=597s)

## LM Studio + AnythingLM & RAG
[利用 LM Studio 跟 AnythingLLM 實作 RAG 系統](https://mybaseball52.medium.com/using-anythingllm-and-lm-studio-to-do-rag-79a962095da1)
[極簡單入門教學!! 免寫程式!! 手把手教你在本地端使用大型語言模型+RAG](https://pipi9baby.medium.com/%E6%A5%B5%E7%B0%A1%E5%96%AE%E5%85%A5%E9%96%80%E6%95%99%E5%AD%B8-%E5%85%8D%E5%AF%AB%E7%A8%8B%E5%BC%8F-%E6%89%8B%E6%8A%8A%E6%89%8B%E6%95%99%E4%BD%A0%E5%9C%A8%E6%9C%AC%E5%9C%B0%E7%AB%AF%E4%BD%BF%E7%94%A8%E5%A4%A7%E5%9E%8B%E8%AA%9E%E8%A8%80%E6%A8%A1%E5%9E%8B-rag-62ab49a07463)
[LM Studio 將下載的模型放到目錄中 注意事項](https://vocus.cc/article/670b3767fd89780001840991)







