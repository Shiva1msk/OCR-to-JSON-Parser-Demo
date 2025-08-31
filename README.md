# OCR-to-JSON Parser Demo

This project is built for the **BeWiser AI Internship Assignment**.  
It extracts text from **PDFs and images** using OCR and outputs the results in **JSON format**.

---

## 🚀 Features
- Works with both **PDFs** and **images (JPG, PNG, etc.)**
- Page-wise text extraction
- Output in clean JSON
- Easy to run on **Google Colab** (no system setup needed)

---

## 📒 Google Colab Demo
You can run the demo here: [Open in Colab](https://colab.research.google.com/drive/1pm6SUXD70jJ2mXKD4fyHfM5v3e8SmRMA?usp=sharing)

---

## ⚡ Local Usage
1. Install requirements:
   ```bash
   pip install -r requirements.txt
Run:

bash
Copy code
python ocr_parser.py sample.pdf
🖼 Example Outputs
✅ File Upload + OCR Results

✅ Code in Action

Output:

json
Copy code
{
    "page_1": "Order confirmation...",
    "page_2": "Ticket 1 of 1..."
}
🛠 Tech Stack
Python

PyMuPDF (fitz)

Pillow

Pytesseract (Tesseract OCR backend)

yaml
Copy code

---

### 📌 What You Need to Do
1. Save your two screenshots (the ones you uploaded) into a local `assets/` folder.  
   - `assets/screenshot_output.png` (the first image with extracted JSON)
   - <img width="1850" height="660" alt="Screenshot 2025-08-31 215654" src="https://github.com/user-attachments/assets/8b91e4da-102f-425b-8fda-dd27c8aac131" />

   - `assets/screenshot_code.png` (the second image with Colab code)
   - <img width="1826" height="471" alt="Screenshot 2025-08-31 215648" src="https://github.com/user-attachments/assets/9859e425-3152-4c41-ba46-0fe64c5bf714" />
