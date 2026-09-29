# 🧠 AI Attention Visualizer

An AI-based web application that extracts text from images using OCR, generates word embeddings, calculates attention scores, and visualizes the attention given to each word.

---

## 🎯 Objective

The objective of this project is to understand how an AI pipeline can process text from an image and visualize attention scores.

The project follows this flow:

**Image → OCR → Extracted Words → Embeddings → Attention → Visualization**

---

## ✨ Features

- 📷 Upload an image containing text
- 🔍 Extract text using OCR
- 📝 Display the extracted text
- 🧠 Generate word embeddings
- 📊 Calculate attention scores
- 📈 Visualize attention scores for individual words
- ⭐ Display the word with the highest attention score
- 🌐 Interactive Streamlit interface

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Tesseract OCR
- Pytesseract
- Sentence Transformers
- NumPy
- Pillow

---

## 📂 Project Structure

```text
AI-Attention-Visualizer/
│
├── app.py
├── ocr.py
├── embedding.py
├── attention.py
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── home.png
    ├── ocr-output.png
    └── attention-output.png

            📷 Image
           │
           ▼
      🔍 OCR
           │
           ▼
    📝 Extracted Text
           │
           ▼
     🔤 Word Splitting
           │
           ▼
    🧠 Word Embeddings
           │
           ▼
    📊 Attention Calculation
           │
           ▼
    📈 Attention Scores
           │
           ▼
    ⭐ Highest Attention