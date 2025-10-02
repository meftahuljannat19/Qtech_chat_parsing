# 🤖 NLP Chat Parsing: Conversation Parser & Keyword Analyzer  

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)  
[![NLTK](https://img.shields.io/badge/NLP-NLTK-green.svg)](https://www.nltk.org/)  
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)  

---

## 📌 Overview  
**Qtech** is a lightweight **conversation analysis tool** that processes raw dialogue logs between a **User** and an **AI chatbot**.  
It extracts structured dialogues, counts messages, and performs **basic keyword analysis** for insights.  

---

## ⚙️ Techniques Used  

- **Text Preprocessing**  
  - File reading, string cleaning (`strip`, `split`)  
  - Parsing conversations into `(speaker, message)` format  

- **Statistical Analysis**  
  - Total number of messages  
  - User vs AI message counts  

- **Keyword Analysis**  
  - Tokenization with **NLTK Punkt**  
  - Stopword filtering  
  - Frequency-based keyword extraction  

---

## 📂 Dataset  

- Input: **`chat.txt`** file  
  - Format:  
    ```
    User: Hello, how are you?
    AI: I’m doing great, thank you.
    User: What can you do?
    AI: I can answer questions and chat with you.
    ```  

---

## 🚀 Getting Started  

### 🔧 Installation  
```bash
# Clone repo
git clone https://github.com/your-username/qtech.git
cd qtech

# Install dependencies
pip install nltk
