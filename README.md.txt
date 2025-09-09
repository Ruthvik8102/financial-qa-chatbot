# 💬 GenAI-powered Financial Q&A Chatbot

A **Generative AI chatbot** built using **LangChain + HuggingFace Transformers + Streamlit**.  
This project demonstrates how **Large Language Models (LLMs)** can be applied in **finance** to answer user queries in real time.  

---

## 🚀 Features
- 🧠 Lightweight HuggingFace model (`distilgpt2`) for text generation  
- 🔗 Integrated with **LangChain** for better prompt handling  
- 💬 Interactive **Streamlit** UI for chatting  
- 📊 Focused on **finance-related Q&A** (mutual funds, credit risk, stock basics, etc.)  
- ⚡ Easily extendable to custom datasets or enterprise use cases  

---

## 📂 Project Structure
financial-qa-chatbot/
│── app.py # Main Streamlit chatbot application
│── requirements.txt # Dependencies
│── README.md # Project documentation

---

## 📦 Installation
Clone the repo:
```bash
git clone https://github.com/your-username/financial-qa-chatbot.git
cd financial-qa-chatbot
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the app:

bash
Copy code
streamlit run app.py
📸 Demo
Example queries and responses:

User Query	Model Response (Sample)
"What is SIP in mutual funds?"	SIP (Systematic Investment Plan) allows investors to invest small amounts regularly in mutual funds, reducing risk through rupee-cost averaging.
"Explain credit risk."	Credit risk is the possibility that a borrower will fail to meet their obligations, leading to financial loss for the lender.
"How does stock market volatility work?"	Volatility measures the degree of variation in stock prices. High volatility means rapid price changes; low volatility indicates stable prices.

📊 Results
Successfully processed finance-related queries with meaningful outputs.

The chatbot generates context-aware, coherent answers for general finance topics.

Demonstrates how even lightweight LLMs can handle domain-focused Q&A when paired with LangChain.

🔮 Future Improvements
📚 Train/fine-tune on finance-specific datasets

🔎 Add RAG (Retrieval-Augmented Generation) with FAISS/ChromaDB

☁️ Deploy on HuggingFace Spaces / Streamlit Cloud

🤖 Experiment with OpenAI GPT / Llama2 for improved accuracy


