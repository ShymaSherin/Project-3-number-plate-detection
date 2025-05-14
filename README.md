# Project-3-number-plate-detection
# 🇮🇳 Indian Vehicle Number Plate Detector

This project is a deep learning and OCR-based application that detects and extracts Indian vehicle number plate text from images using **EasyOCR**, **OpenCV**, and **Gradio** for a user-friendly interface.

## 🚀 Features

- Detects vehicle number plates from uploaded images
- Uses EasyOCR to recognize the text on number plates
- Image preprocessing using OpenCV
- Simple and interactive web UI via Gradio
- Dataset loaded from Google Drive (customizable path)

## 🛠️ Technologies Used

- Python
- OpenCV
- EasyOCR
- Gradio
- NumPy
- TensorFlow/Keras (not actively used in this version)
- Google Colab (recommended for running)

---

## 📁 Dataset

The dataset should contain images of Indian vehicles with visible number plates.

Place your dataset in your Google Drive and update the path accordingly in the script:

```python
DATASET_PATH = '/content/drive/My Drive/Indian_Number_Plates'
