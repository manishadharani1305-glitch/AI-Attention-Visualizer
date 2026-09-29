# 🧠 AI Attention Visualizer

AI Attention Visualizer is a Streamlit-based application that extracts text from an image using OCR, converts the extracted words into embeddings, calculates attention scores, and visualizes the attention given to each word.

## 🎯 Objective

The objective of this project is to understand how an AI pipeline processes text from an image and visualizes attention scores.

### Project Flow

**Image → OCR → Extracted Words → Embeddings → Attention → Visualization**

---

## ✨ Features

- 📷 Upload an image containing text
- 🔍 Extract text using Tesseract OCR
- 📝 Display the extracted text
- 🧠 Generate word embeddings
- 📊 Calculate attention scores
- 📈 Visualize word-level attention scores
- ⭐ Display the word with the highest calculated attention score
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
    ├──<img width="1427" height="933" alt="Screenshot 2026-09-29 210743" src="https://github.com/user-attachments/assets/6d846c2e-090e-4c06-80c2-65aaa2e18f2a" />

    ├── <img width="1161" height="921" alt="Screenshot 2026-09-29 210754" src="https://github.com/user-attachments/assets/3f592d8a-6a47-437c-8c58-c4d1d63b202f" />

    ├──<img width="1341" height="942" alt="Screenshot 2026-09-29 210806" src="https://github.com/user-attachments/assets/fefea7d5-19cc-4523-9576-93fa37e42b07" />

    └── <img width="1175" height="806" alt="Screenshot 2026-09-29 210815" src="https://github.com/user-attachments/assets/cd76041e-42d7-4378-ade0-e46717161810" />

## 🔄 How It Works

### 1. 📷 Image Upload

The user uploads an image containing text.

### 2. 🔍 OCR

Tesseract OCR extracts text from the uploaded image.

### 3. 📝 Text Processing

The extracted text is split into individual words and unnecessary punctuation is removed.

### 4. 🧠 Embeddings

The extracted words are converted into numerical vector representations using the Sentence Transformer model:

`all-MiniLM-L6-v2`

### 5. 📊 Attention Calculation

The generated embeddings are used to calculate attention scores using Query, Key, and Value matrices.

### 6. 📈 Visualization

The calculated attention scores are displayed using Streamlit progress bars.

The word with the highest calculated attention score is also displayed.

---

# 📸 Project Screenshots

## 🖥️ Streamlit Application

![Streamlit Application](screenshots/home.png)

The screenshot above shows the main interface of the AI Attention Visualizer.

---

## 📝 OCR Extracted Text

![OCR Extracted Text](screenshots/ocr-output.png)

This screenshot shows the text extracted from the uploaded image using OCR.

---

## 🧠 Word Attention

![Word Attention](screenshots/attention-output.png)

This screenshot shows the calculated attention scores for the extracted words.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/AI-Attention-Visualizer.git

Move into the project folder:

```bash
cd AI-Attention-Visualizer

        📷 Image
           │
           ▼
       🔍 OCR
           │
           ▼
    📝 Extracted Text
           │
           ▼
      🔤 Words
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
