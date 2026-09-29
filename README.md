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
    ├── <img width="1427" height="933" alt="Screenshot 2026-09-29 210743" src="https://github.com/user-attachments/assets/43fcbbf2-434a-41e5-89f2-31c4694d5558" />

    ├── <img width="1161" height="921" alt="Screenshot 2026-09-29 210754" src="https://github.com/user-attachments/assets/400dccb5-e947-486a-a851-69c55f937c71" />
    
    ├──<img width="1341" height="942" alt="Screenshot 2026-09-29 210806" src="https://github.com/user-attachments/assets/f03e2fbb-8527-44f2-862c-dc4e745dc5b3" />

    └── <img width="1175" height="806" alt="Screenshot 2026-09-29 210815" src="https://github.com/user-attachments/assets/3b4a2bd2-ae91-4ce8-9e3d-d927d7ceeed6" />


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
