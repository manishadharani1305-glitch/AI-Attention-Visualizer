# 🧠 AI Attention Visualizer

AI Attention Visualizer is a Streamlit-based application that extracts text from an image using OCR, converts the extracted words into embeddings, calculates attention scores, and visualizes the attention given to each word.

---

## 🎯 Objective

The objective of this project is to understand how an AI pipeline processes text from an image and visualizes attention scores.

The project follows this flow:

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

- **Python**
- **Streamlit**
- **Tesseract OCR**
- **Pytesseract**
- **Sentence Transformers**
- **NumPy**
- **Pillow**

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
└── README.md

---

## 🔄 How It Works

### 1. 📷 Image Upload

The user uploads an image containing text through the Streamlit application.

### 2. 🔍 OCR

Tesseract OCR extracts text from the uploaded image.

### 3. 📝 Text Processing

The extracted text is split into individual words.

Punctuation is removed and words with fewer than three characters are filtered out.

The application processes up to 20 words.

### 4. 🧠 Embeddings

The extracted words are converted into numerical vector representations using the Sentence Transformer model:

**`all-MiniLM-L6-v2`**

### 5. 📊 Attention Calculation

The generated embeddings are used to calculate attention scores using **Query, Key, and Value matrices**.

The attention mechanism uses scaled dot-product attention.

### 6. 📈 Visualization

The calculated attention scores are displayed using Streamlit progress bars.

The application also displays the word with the highest calculated attention score.

---

## 🧩 Project Workflow

```text
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

   ---

## 📸 Project Output

### 🖥️ Streamlit Application

The following screenshot shows the AI Attention Visualizer running in the Streamlit interface.

<img width="1427" height="933" alt="Screenshot 2026-09-29 210743" src="https://github.com/user-attachments/assets/b05425d5-ec16-4ab1-b0fa-58bd4ff8155e" />


---

### 📝 OCR Extracted Text

The following screenshot shows the text extracted from the uploaded image using Tesseract OCR.

<img width="1161" height="921" alt="Screenshot 2026-09-29 210754" src="https://github.com/user-attachments/assets/bc0a03b2-3acd-4b39-b620-180fd4b6008a" />


---

### 🧠 Word Attention Scores

The following screenshot shows the calculated attention scores for the extracted words.

<img width="1341" height="942" alt="Screenshot 2026-09-29 210806" src="https://github.com/user-attachments/assets/dedbfcad-62fb-41c8-8e6f-7da3caad0bb0" />

---

### ⭐ Highest Attention

The application displays the word with the highest calculated attention score.

<img width="1175" height="806" alt="Screenshot 2026-09-29 210815" src="https://github.com/user-attachments/assets/331b8bea-4d58-424a-baed-5bdad1d453d4" />
