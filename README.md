# OCR Preprocessing for Noisy Text Images

This project demonstrates how to use Python and Tesseract OCR to extract text from noisy or distorted images, such as CAPTCHA-like samples.

## 🚀 Overview

The notebook/script applies basic image preprocessing techniques to improve OCR accuracy:

* Grayscale conversion
* Image binarization (thresholding)
* Debug image outputs for each stage

It is intended for learning and experimentation with OCR pipelines.

## 🛠️ Tech Stack

* Python
* Pillow (PIL)
* pytesseract (Tesseract OCR)

## 📂 Workflow

1. Load input image
2. Save original (for debugging)
3. Convert to grayscale
4. Apply binarization
5. Run OCR using Tesseract
6. Output extracted text

## ▶️ Usage

```bash
pip install pillow pytesseract
```

Make sure Tesseract OCR is installed on your system.

Then run:

```python
python your_script.py
```

Update the image path as needed.

## ⚠️ Disclaimer

This project is for educational and research purposes only.

Do not use this code to bypass security mechanisms or violate the terms of service of any website. Always ensure you have permission before automating or extracting data from online services.

## 📌 Notes

* OCR accuracy depends heavily on image quality
* Adjust threshold values for better results
* More advanced techniques (denoising, contour detection, ML models) can further improve performance

## 📖 Future Improvements

* Adaptive thresholding
* Noise removal filters
* Deep learning-based OCR models
