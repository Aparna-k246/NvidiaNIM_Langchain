# 🤖 NvidiaNIM_Langchain — RAG Q&A with NVIDIA NIM + LangChain

This project demonstrates a Retrieval-Augmented Generation (RAG) system that leverages **NVIDIA NIM APIs** for LLM inference and **LangChain** for document loading, chunking, and vector-based retrieval. It allows users to ask natural language questions over PDF files like US Census reports.

---

## 📁 Project Structure

- `app.py`: Basic example of streaming inference from NVIDIA NIM using the LLaMA3-70B model.
- `app1.py`: Streamlit-based interface for uploading PDFs and performing Q&A using LangChain and NIM.
- `us_census/`: Contains example census PDFs used for document QA.
- `requirements.txt`: Required Python packages.
- `.env` (user-provided): For securely storing your NVIDIA NIM API key.

---

## ✅ Features

- PDF document ingestion and chunking  
- Embedding and vector storage using FAISS  
- Contextual retrieval with LangChain  
- Answer generation using NVIDIA NIM-hosted `meta/llama3-70b-instruct`  
- Optional Streamlit UI for interaction  
- Streaming response support  

---

## 🚀 How to Use

1. Clone the repository and install dependencies  
2. Add your NVIDIA API key to a `.env` file  
3. Run `app.py` for a quick streaming inference test  
4. Run `app1.py` with Streamlit to interactively upload PDFs and ask questions  

You can upload your own PDFs or use the sample reports in the `us_census` folder.

---

## 🔐 NVIDIA NIM

NVIDIA NIM (NVIDIA Inference Microservices) provides scalable and hosted endpoints for LLM inference using models like LLaMA3, Mixtral, Mistral, etc. This project integrates with NIM via OpenAI-compatible APIs for production-grade reliability and streaming.

More: [NVIDIA NIM Overview](https://developer.nvidia.com/blog/introducing-nvidia-nim/)

---

## 📚 Sample Questions

- What trends are reported in acsbr-017?
- What income distribution is described in p70-178?
- Which PDF discusses housing patterns?

---

## 📦 Tech Stack

- Python
- NVIDIA NIM (via OpenAI SDK)
- LangChain
- FAISS
- Streamlit
- PyMuPDF
- dotenv

---

## 📄 License

Licensed under the MIT License. See the `LICENSE` file for details.

---

## 👩‍💻 Author

**Aparna K**  
[GitHub](https://github.com/Aparna-k246) • [LinkedIn](https://www.linkedin.com/in/aparna-k-628005167/)

---

## 🌐 Related Repos

- [GENAI-Projects-Langchain](https://github.com/Aparna-k246/GENAI-Projects-Langchain)
- [Gen-AI_Google-Gemini](https://github.com/Aparna-k246/Gen-AI_Google-Gemini)
- [Langgraph_apps](https://github.com/Aparna-k246/Langgraph_apps)
