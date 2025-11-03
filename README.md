# Smart-Document-Scanner
# 🧠 Smart Document Scanner with OCR (Phase 14 + Drive Upload)

A **Tkinter-based desktop application** that lets you upload or capture images, extract text using **OCR (Optical Character Recognition)**, translate the extracted text, format it with text editing tools, annotate images, and export or upload your work to **Google Drive**.

---

## 🚀 Features

✅ **Upload or Capture Images**  
- Upload images from your computer or capture directly using your webcam.

✅ **Extract Text (OCR)**  
- Uses **Tesseract OCR** to extract text from images.  
- Supports multiple languages — English, Hindi, Telugu, Tamil.

✅ **Translate Extracted Text**  
- Instantly translate extracted text to another language using **GoogleTranslator** (via `deep-translator`).

✅ **Text Formatting Tools**  
- Apply **bold**, **italic**, **underline**, and **highlight colors** to selected text.  
- Change **font family** and **font size** dynamically.

✅ **Search & Highlight Text**  
- Search within the text box and highlight matches in real time.

✅ **Annotate Images**  
- Draw annotations directly on uploaded images using the mouse.  
- Save annotated versions instantly.

✅ **Save or Export Text**  
- Save extracted or translated text as:
  - `.txt` (Plain Text)
  - `.pdf` (PDF File)
  - `.docx` (Word Document with formatting)

✅ **Google Drive Upload (Optional)**  
- After saving, automatically uploads files to your **Google Drive** (if Drive API is configured).

---

## 🧩 Tech Stack

| Component | Library / Tool |
|------------|----------------|
| GUI | Tkinter, ttk, ScrolledText |
| OCR | pytesseract, Tesseract-OCR |
| Image Handling | Pillow (PIL) |
| PDF Export | FPDF |
| Word Export | python-docx |
| Translation | deep-translator |
| Webcam Capture | OpenCV |
| Cloud Upload | Google Drive API (optional) |

---

## ⚙️ Installation

### 1️⃣ Clone or Download the Project
```bash
git clone https://github.com/yourusername/smart-document-scanner.git
cd smart-document-scanner
