# 🏥 OCT Disease Detection using Deep Learning  

## 📌 Overview  
This project leverages **deep learning** techniques for the **automated classification** of retinal **Optical Coherence Tomography (OCT) images** into four categories:  

✅ **Choroidal Neovascularization (CNV)**  
✅ **Diabetic Macular Edema (DME)**  
✅ **Drusen**  
✅ **Normal**  

Manual OCT image analysis is **time-consuming** and prone to **inter-observer variability**. To address this, we implemented **CNN, ResNet, and AlexNet**, achieving **state-of-the-art performance** in medical image classification.  

---

## 📂 Dataset  
The dataset used consists of **retinal OCT images** obtained from publicly available sources.  

🔗 **Dataset Link:** [https://www.kaggle.com/datasets/paultimothymooney/kermany2018]  

---

## 🏗️ Models Implemented  
We evaluated three deep learning architectures:  

📌 **Convolutional Neural Network (CNN)**  
📌 **ResNet (Residual Network)**  
📌 **AlexNet**  

### 🔍 **Performance Metrics**  
| Model   | Accuracy | Precision | Recall | F1-Score |  
|---------|---------|-----------|--------|----------|  
| **ResNet** | **95%** | High | High | High |  
| **AlexNet** | 91% | - | - | - |  
| **CNN** | 85% | - | - | - |  

🚀 **ResNet achieved the highest accuracy (95%)**, making it the most effective model for OCT image classification.  

---

## ⚙️ Installation & Dependencies  
To run this project, install the required dependencies:  

```bash
pip install tensorflow keras numpy matplotlib opencv-python scikit-learn
