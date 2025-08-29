# RAG-Powered-PDF-Chat
Chat with PDFs lets you upload documents and ask questions in plain language. Powered by Google Gemini + RAG, it gives accurate answers directly from your PDFs.


# 📄 Chat with PDFs (**RAG-based PDF Q&A App**)


An interactive Streamlit application that allows users to upload PDF files and ask natural language questions. The system uses LangChain, Google Generative AI (Gemini), and FAISS vector database to extract answers from the uploaded documents.

## 🚀 Features  

- 📁 **Upload single or multiple PDFs**  
- 🔍 **Extracts and processes text from PDFs**  
- ✂️ **Splits large text into manageable chunks** using `RecursiveCharacterTextSplitter`  
- 🧠 **Embeds chunks with Google Generative AI Embeddings**  
- 📦 **Stores embeddings in FAISS Vector Store**  
- 🤖 **Uses RAG (Retrieval Augmented Generation) for Q&A**  
- 💬 **Interactive Streamlit UI**

- ## 🛠️ Tech Stack  

- 🐍 **Python**  
- 🎨 **Streamlit**  
- 🔗 **LangChain**  
- 🌌 **Google Generative AI (Gemini)**  
- 📦 **FAISS**  
- 📑 **PyPDF2**

- ## 📂 Project Structure  

├── app.py # Main Streamlit app

├── requirements.txt # Required dependencies

├── .env # Store your Google API key

└── faiss_index/ # Generated FAISS index after processing PDFs

## 📸 **Screenshots**
### 🖼️ **1. App Homepage** 
<img width="1913" height="979" alt="Screenshot 2025-08-26 202317" src="https://github.com/user-attachments/assets/068824cf-8a92-4374-9c23-ee438b64836b" />


### 🖼️ **2. Uploading PDFs**  
<img width="1919" height="940" alt="Screenshot 2025-08-26 202745" src="https://github.com/user-attachments/assets/12d4e2da-4280-4727-ac81-be60a8a4c461" />
<img width="1904" height="906" alt="Screenshot 2025-08-26 202804" src="https://github.com/user-attachments/assets/06f3b0fd-1353-4360-bda8-2ce64ebf7041" />


### 🖼️ **3. Asking a Question**  
<img width="1901" height="914" alt="Screenshot 2025-08-26 204934" src="https://github.com/user-attachments/assets/95510b77-0e4d-406f-bd22-015d67922fd4" />
<img width="1894" height="912" alt="Screenshot 2025-08-26 204450" src="https://github.com/user-attachments/assets/7cbb7955-1469-4db1-a318-adbb7aeff6e4" />
<img width="1901" height="909" alt="Screenshot 2025-08-26 204359" src="https://github.com/user-attachments/assets/1c864ce5-a041-47ee-a8da-aaa8b30889af" />
<img width="1908" height="926" alt="Screenshot 2025-08-26 203519" src="https://github.com/user-attachments/assets/ea81d6aa-7c16-4968-964c-5c92c77fcf2a" />
<img width="1904" height="918" alt="Screenshot 2025-08-26 203044" src="https://github.com/user-attachments/assets/6706f7ab-251f-423f-8d86-5db84116f991" />

## 🧑‍💻 How to Run

1. Clone this repo to your computer.  
2. Open terminal and go to the project folder: `cd RAG-Powered-PDF-Chat`  
3. Install dependencies: `pip install -r requirements.txt`  
4. Run the app: `streamlit run app.py`  
5. Open the link shown in the terminal to use the app.

## 📜 License

This project is licensed under the **MIT License**.

## 🔗 Connect with Me

[LinkedIn](https://www.linkedin.com/in/sinega-magesh-752b8332b/)




