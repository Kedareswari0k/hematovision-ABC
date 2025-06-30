# Hematovision
advanced blood cell classification using transfer learning
 

**HematoVision** is a deep learning-powered web application designed to classify microscopic images of blood cells into one of four categories:

- 🔴 **Eosinophil**
- 🟢 **Lymphocyte**
- 🟡 **Monocyte**
- 🔵 **Neutrophil**

This intelligent diagnostic tool leverages **Transfer Learning with MobileNetV2** to deliver high-accuracy predictions in real-time, wrapped in a clean and intuitive **Flask-based web interface**.

---

## 🚀 How It Works

1. 📤 Upload a microscopic image of a blood cell.
2. 🔍 The model processes the image using deep learning.
3. 📈 You get the predicted class along with a preview of the uploaded image.

This makes **HematoVision** an ideal assistant for biomedical learners, educators, and early-stage researchers.

---

## ⚙️ Features

- ✅ Real-time image classification
- ✅ Built-in preprocessing pipeline with OpenCV
- ✅ Lightweight model (MobileNetV2) for quick inference
- ✅ Web interface with smooth UX and visual feedback
- ✅ Base64 image embedding for fast, secure previews

---

## 🛠️ Tech Stack

| Layer      | Technologies Used                      |
|------------|----------------------------------------|
| **Model**  | TensorFlow / Keras with MobileNetV2    |
| **Backend**| Python, Flask                          |
| **Image Ops**| OpenCV for image preprocessing       |
| **Frontend**| HTML5, CSS3 (light theme with UI)     |

---

### 📁 Project Structure

```bash
SMARTBRIDGE INTERN/
├── __pycache__/
├── documents/
    ├──Projectreport1.pdf
├── static/
└── templates/          
    ├── home.html        
    └── result.html      
├── venv/
├── .gitignore
├── app.py
├── Bloodcell.h5
├── requirements.txt
```

---

### Start the Flask App

```bash
python app.py
```

Then open your browser and go to:
🔗 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📸 Sample Output

> 🧠 The application shows the predicted blood cell type alongside the uploaded image, providing instant visual confirmation.

---
