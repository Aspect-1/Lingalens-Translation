1. First Install dependencies by this code:
 `pip install -r requirements.txt`
2. Then for OCR install tesseract if not installed from `https://github.com/UB-Mannheim/tesseract/wiki`
3. After installing tesseract copy the path from your program files e.g. `C:\Program Files\Tesseract-OCR`
4. Then search Edit Environment Variables and click environment variables
5. choose Path `User variable` and click edit option then add the copied path by clicking new button
6. After that open cmd and check the tesseract version by `tesseract --version` if it shows error then check the added path in systemvariables
7. In command line write 'python app.py'
8. It will run nicely

# LingaLens: Multilingual Text Translation System

A web-based application that extracts and translates text from images, PDFs, and plain text into multiple languages.  
Developed as a **minor project with a team of 4**, where I was responsible for the **frontend and backend development (web app)**.

## Features
- Extracts text from images and scanned PDFs using **PyTesseract + OpenCV preprocessing** (~20% improvement in accuracy).
- Translates extracted text into 6 languages using Hugging Face models (NLLB-200, M2M100, MarianMT).
- Supports multiple input formats (images, PDFs, plain text).
- Simple, responsive web interface with **HTML, CSS, JS**.
- Backend integration with **Python** and **MongoDB Atlas** for user authentication and data storage.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (Flask/Django if used), MongoDB Atlas  
- **Libraries:** OpenCV, PyTesseract, PyMuPDF, pdf2image  
- **NLP Models:** Hugging Face Transformers (NLLB-200, M2M100, MarianMT)

## My Contribution
I built the **web interface and backend logic**, connecting the OCR + translation pipeline with a user-friendly web application.
