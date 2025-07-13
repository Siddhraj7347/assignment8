# 🧠 Loan Approval RAG Chatbot

A Retrieval-Augmented Generation chatbot that answers questions about loan applications using semantic search and OpenAI GPT.

## 📁 Dataset

- Source: [Kaggle](https://www.kaggle.com/datasets/sonalisingh1411/loan-approval-prediction)

## ⚙️ Setup

```bash
pip install -r requirements.txt
```

Optional: Enable Jupyter widgets

```bash
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension
```

## 🔐 API Key

In `loan_rag_chatbot.ipynb`, set your OpenAI API key:

```python
openai.api_key = "your-api-key"
```

## ▶️ Run

```bash
jupyter notebook loan_rag_chatbot.ipynb
```

## 💬 Example Questions

- What are common loan amounts for applicants with high income?
- Tell me about applicants who got their loans approved.
- Why are some loans rejected?

## 📦 Dependencies

See `requirements.txt`

## 📄 License

MIT License
