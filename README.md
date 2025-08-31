# Usagi-AI-

# Helmet & License Plate Detection 🚦🪖

This project combines **YOLOv8** object detection with **OCR (EasyOCR / Tesseract)** to detect:  
- Whether a rider is **wearing a helmet** or **not wearing a helmet**.  
- Recognize and extract the **vehicle license plate number** from images.  

The project runs seamlessly on **Google Colab**.  

---

## 📌 Features  

✅ Helmet detection (Helmet / No-Helmet classification)  
✅ License plate detection using YOLO bounding boxes  
✅ License plate number recognition using **OCR (Tesseract / EasyOCR)**  
✅ Works on both **images** and **real-time video feeds** (with minor tweaks)  
✅ Output shows bounding boxes with labels & recognized plate number  

---

## 🛠️ Tech Stack  

- 🐍 Python 3  
- 🚀 YOLOv8 (Ultralytics)  
- 🎥 OpenCV  
- 🔎 EasyOCR / Tesseract OCR  
- ☁️ Google Colab (for running without local setup)  

---

## 📂 Project Structure  

```bash
Helmet-Plate-Detection/
│
├──weights
📦 best.pt              # YOLO trained model weights (License Plate)
🪖 helmet_best.pt        # YOLO helmet detection weights
├──app..py                #python file
├── 🖼️ demo_image.jpg        # Sample input image
├── 📒 app.ipynb           # Google Colab notebook
├── 📜 requirements.txt     # Python dependencies
└── 📘 README.md            # Project documentation
```

### 2️⃣ Install Dependencies  

Make sure you are inside the project folder, then install dependencies from `requirements.txt`:  

```bash
cd Helmet-Plate-Detection
pip install -r requirements.txt
```

3️⃣ Run on Google Colab
```bash

	•	Upload best.pt (license plate detection weights)
	•	Upload helmet_best.pt (helmet detection weights)
	•	Open usagi.ipynb in Colab and run the cells
```

