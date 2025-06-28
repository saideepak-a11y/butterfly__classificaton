# 🦋 Enchanted Wings: Butterfly Species Classifier

**By G. Himanjali**

**Video Link**: https://drive.google.com/file/d/1uWuGeNQl2RQajHkwoU4Ay9OU-dZKIHbL/view?usp=sharing

---

## 🌟 Overview

Enchanted Wings is a Flask-based web application that classifies images of butterflies using transfer learning with the VGG16 model. Trained on a dataset of **6,499 images across 75 species**, the project achieves fast and accurate classification.

---

## 🧠 Features

- **Transfer Learning** with VGG16 for efficient and accurate training  
- **Web interface** built with Flask for image upload and prediction  
- **Responsive UI** with background overlay, image preview, and styled buttons  
- **About** and **Contact** pop-ups for project & developer details

---

## 🚀 Live Demo & Screenshots

### 1. Home Page  
<img width="956" alt="image" src="https://github.com/user-attachments/assets/d5c1401a-9e00-410c-b408-dbb5eb57cdac" />


The homepage features a full-screen butterfly background. Navigate via the navbar.

---

### 2. Upload & Predict  
<img width="959" alt="image" src="https://github.com/user-attachments/assets/c04d674b-8f5a-4825-ad9a-9a1055d9cd30" />



Go to "Predict" → upload an image → preview appears → click "Predict" to get results.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/d56ff92b-97d7-4b55-91f1-9355e042de48" />


---


---

## ⚙️ How It Works

1. **Image Upload:** User selects an image file; preview is shown.  
2. **Prediction Request:** On submitting, the image is sent to Flask backend.  
3. **Model Inference:** The `app.py` script loads `vgg16_model.h5`, preprocesses the image, and predicts the species.  
4. **Display Result:** The predicted butterfly name is returned and shown on the webpage.
<img width="954" alt="image" src="https://github.com/user-attachments/assets/50b5d0e3-f4bb-4c58-a85f-452d73348a5c" />




### 3. About & Contact  
<img width="946" alt="image" src="https://github.com/user-attachments/assets/f16e94e8-e741-4dac-b764-148854d41ddf" />



"About" and "Contact" open in new windows with project and developer details.
<img width="947" alt="image" src="https://github.com/user-attachments/assets/552d663c-d799-4b22-984d-4d47ceeb53b8" />

---

## 🧩 Setup Instructions

```bash
# Clone repository
git clone https://github.com/Anju-93905063/butterfly_classification.git
cd butterfly_classification

# Set up Python virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Download dataset and train model (Colab or local)
# Save trained model as 'vgg16_model.h5' in the project root

# Run the app
python app.py


