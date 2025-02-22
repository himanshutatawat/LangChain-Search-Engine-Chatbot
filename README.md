# 🔎 LangChain - Chat with Search Engine 🌍  

This project is an **AI-powered chatbot** that integrates **LangChain, FAISS, Wikipedia, Arxiv, and DuckDuckGo Search**. It allows users to interact with an AI assistant that retrieves **real-time search results** from various sources.  

---

## ✨ Features  
✅ **Conversational AI** – Chat with an AI assistant that understands queries.  
✅ **Live Search Integration** – Fetch real-time data from **Wikipedia, Arxiv, and DuckDuckGo**.  
✅ **FAISS Vector Search** – Stores and retrieves embeddings for relevant responses.  
✅ **Groq API with Llama3-8b-8192** – Uses an advanced language model for intelligent responses.  
✅ **Error Handling** – Prevents parsing errors for smooth user experience.  
✅ **Streamlit UI** – Simple & interactive chatbot interface.  

---

## 🛠️ Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/langchain-search-chat.git
cd langchain-search-chat
```
### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Set Up Environment Variables
Create a .env file in the root directory and add the following:

```ini

GROQ_API_KEY="your-groq-api-key"
```
Replace "your-groq-api-key" with your actual API key.

### 5️⃣ Run the Application
```bash

streamlit run app.py
```
Then, open the Streamlit app in your browser and start chatting!

### 📁 Project Structure
```bash

📂 langchain-search-chat
│-- 📜 app.py                  # Main Streamlit chatbot script
│-- 📜 requirements.txt        # Required dependencies
│-- 📜 .env                    # Environment variables (ignored in .gitignore)
│-- 📜 README.md               # Project documentation
```
### 🎯 How to Use
1️⃣ Enter your Groq API key in the sidebar.
2️⃣ Ask questions using the chat input.
3️⃣ The assistant will search Wikipedia, Arxiv, and DuckDuckGo for relevant information.
4️⃣ Responses will be displayed in the chat interface.

### 📦 Dependencies
This project requires the following Python packages:

streamlit
langchain
langchain_groq
langchain_community
langchain_text_splitters
faiss-cpu
python-dotenv
duckduckgo-search
wikipedia-api
arxiv
### To install all dependencies, run:

```bash

pip install -r requirements.txt
```
