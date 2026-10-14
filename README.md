# 🎫 Customer Support Ticket Routing System

### 🤖 An NLP-Based Ticket Classification Prototype Using Python & spaCy

A Natural Language Processing (NLP) project that analyzes customer support messages and suggests the most relevant department using semantic similarity, rule-based pattern matching, and Named Entity Recognition (NER).

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/NLP-8A2BE2?style=for-the-badge" alt="NLP"/>
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
</p>

---

## 📌 Project Overview

Customer support teams receive requests related to payments, technical problems, refunds, and product inquiries. Manually assigning every ticket can take time.

This project explores how NLP techniques can analyze incoming messages and recommend a suitable support department.

## ✨ Key Features

- 🧠 **Semantic Similarity:** Compares customer messages with predefined department examples.
- 🔎 **Pattern Matching:** Uses spaCy's `Matcher` to identify relevant words and phrases.
- 🏷️ **Named Entity Recognition (NER):** Extracts entities such as organizations, dates, and quantities.
- 📊 **Department Ranking:** Ranks candidate departments using calculated similarity scores and matching rules.
- 👨‍💻 **Manual Review:** Supports flagging uncertain classifications for human review.

## 🏢 Supported Departments

| Department | Example Request |
|---|---|
| 💳 Billing Team | Payment failed or incorrect charge |
| 🛠️ Technical Team | Login issues or application errors |
| 💰 Refund Team | Refund status or refund requests |
| 🛍️ Sales Team | Product information or discount inquiries |

*Examples are illustrative; actual routing depends on the reference examples and rules implemented in the notebook.*

## 🛠️ Technology Stack

- 🐍 Python
- 🧠 spaCy
- 📚 `en_core_web_md` language model
- 📓 Jupyter Notebook
- 🔍 NLP and rule-based text processing

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/SumanKumar18/customer-support-ticket-routing.git
cd customer-support-ticket-routing
```

### 2️⃣ Install dependencies

```bash
pip install spacy jupyter
```

### 3️⃣ Download the spaCy language model

```bash
python -m spacy download en_core_web_md
```

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the `Customer Support Ticket Routing .ipynb` notebook and execute the cells in order.

## 🔄 How It Works

1. 📥 Receive a customer support message.
2. 🧹 Process the message using spaCy.
3. 🧠 Compare the message against predefined department examples.
4. 🔎 Identify relevant patterns using the Matcher.
5. 🏷️ Extract named entities from the message.
6. 📊 Calculate and rank department scores.
7. ✅ Suggest a department or flag the ticket for manual review.

## 📂 Project Structure

```text
customer-support-ticket-routing/
│
├── Customer Support Ticket Routing .ipynb
└── README.md
```

## 📈 Current Scope & Limitations

This project is an exploratory prototype based on predefined reference examples and rules. Its calculated routing scores are heuristic scores, not validated classification accuracy.

Further testing on a labeled dataset is needed to measure classification performance and reliability.

## 🚀 Future Enhancements

- 📊 Evaluate classification performance using a labeled dataset.
- 🤖 Explore supervised machine learning for ticket classification.
- 🌐 Develop a web interface using Flask or Streamlit.
- 📈 Add performance metrics and visualizations.
- 🔗 Explore integration with customer support workflows.

## 🎯 Learning Outcomes

- Understanding practical NLP pipelines.
- Applying semantic similarity to text classification.
- Implementing rule-based pattern matching.
- Exploring Named Entity Recognition.
- Structuring and documenting a Python project for GitHub.

## 👨‍💻 Author

**Suman Kumar Teja**

🔗 GitHub: [@SumanKumar18](https://github.com/SumanKumar18)

---

⭐ If you find this project interesting, feel free to explore the code and share suggestions for improvement!

💬 Feedback and contributions are welcome.
