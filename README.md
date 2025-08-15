# 🌿 Cotton Plant Health Classification

## 📌 Overview
The **Cotton Plant Health Classification** project uses **deep learning** and **computer vision** to detect and classify common diseases in cotton plants from leaf images.  
A **Convolutional Neural Network (CNN)** is trained to identify whether a leaf is healthy or affected by a specific disease, helping farmers take timely action to protect crops.

---

## 📂 Dataset
- **Source:** [Kaggle – Cotton Plant Disease Dataset](https://www.kaggle.com/datasets/dhamur/cotton-plant-disease?resource=download)  
- **Download:** You must log in to Kaggle and download the dataset manually from the link above.  
- **Total Images:** 3,118  
- **Classes:**
  - Aphids  
  - Army Worm  
  - Bacterial Blight  
  - Powdery Mildew  
  - Target Spot  
  - Healthy  

---

## 🛠 Methodology
1. **Data Preprocessing** – resizing, normalization, and cleaning.  
2. **Data Augmentation** – rotation, flipping, brightness adjustment, zoom.  
3. **Model Training** – CNN built using TensorFlow/Keras.  
4. **Evaluation** – accuracy measurement and confusion matrix.  

---

## 📊 Results
- **Accuracy:** 88% after 20 epochs  
- Potential for improvement with more epochs, hyperparameter tuning, and transfer learning.

---

## 🚀 Future Work
- Improve accuracy with advanced architectures (EfficientNet, ResNet).  
- Add more disease types.  
- Convert to **TensorFlow Lite** for mobile apps.  
- Develop a **React + Flask** web interface.  
- Integrate with IoT devices for real-time monitoring.  

---

## 💻 Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib  
- **Tools:** Google Colab, Jupyter Notebook  

---

## 📦 Installation
```bash
# Clone repository
git clone https://github.com/yourusername/cotton-plant-health-classification.git
cd cotton-plant-health-classification

# Install dependencies
pip install -r requirements.txt
