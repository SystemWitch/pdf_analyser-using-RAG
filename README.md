# 📚 Chat with Multiple PDFs

Interact with multiple PDF files using powerful AI models like **Gemini 1.5 (Google AI)** to extract insights, analyze financial data, and answer questions based on uploaded documents. This app is especially useful for analyzing **annual reports** and **financial statements** of Indian stock market companies.

---

## 🚀 Features

- 📄 Upload multiple PDF files
- 🤖 Ask questions based on the content of the PDFs
- 🧠 Uses LangChain and Google Gemini 1.5 (`gemini-1.5-flash`) for contextual answers
- 🗃️ Embeds content using `GoogleGenerativeAIEmbeddings` and stores in FAISS vector database
- 📊 Specialized for analyzing financial reports, related-party transactions, and remuneration
- 🗨️ Chat-like interface with user/bot avatars
- 📥 Export conversation history as CSV

---

## 📦 Tech Stack

| Tech       | Purpose                                  |
| ---------- | ---------------------------------------- |
| Streamlit  | UI framework for interactive web apps    |
| LangChain  | Managing LLM chains and embeddings       |
| Gemini 1.5 | Large Language Model (via Google AI API) |
| PyPDF2     | PDF text extraction                      |
| FAISS      | Vector database for similarity search    |
| Pandas     | Exporting conversation as CSV            |
| HTML/CSS   | Custom chat UI inside Streamlit          |

---

## 🧠 Prompt Template Logic

This tool is **finance-aware**. The prompt guides the LLM to:

- Evaluate financial statements from PDFs
- Detect irregularities or red flags
- Analyze related party transactions
- Identify unusual managerial remuneration

---

## 🧪 Sample Use Cases

- Analyze 5 annual reports to compare **debt-to-equity ratios**
- Identify suspicious **related-party transactions**
- Audit **CFO to Net Profit** conversion trends
- Track increase in **Key Managerial Personnel (KMP)** pay

---

## 📄 License

MIT License – Feel free to use, modify, and share!
