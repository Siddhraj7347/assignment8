# 🧠 Loan Approval RAG Chatbot

A Retrieval-Augmented Generation chatbot that answers questions about loan applications using semantic search and OpenAI GPT.

## 📁 Dataset

- Source: [Kaggle](https://www.kaggle.com/datasets/sonalisingh1411/loan-approval-prediction)

## ⚙️ Setup

```bash
pip install -r requirements.txt
Optional: Enable Jupyter widgets

bash
Copy
Edit
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension
🔐 API Key
In loan_rag_chatbot.ipynb, set your OpenAI API key:

python
Copy
Edit
openai.api_key = "your-api-key"
▶️ Run
bash
Copy
Edit
jupyter notebook loan_rag_chatbot.ipynb
💬 Example Questions
What are common loan amounts for applicants with high income?

Tell me about applicants who got their loans approved.

Why are some loans rejected?

📦 Dependencies
See requirements.txt

📄 License
MIT License

yaml
Copy
Edit

---

### ✅ 3. `requirements.txt`

```txt
pandas
numpy
faiss-cpu
sentence-transformers
openai==0.28
kagglehub
ipywidgets****
