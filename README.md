# 🍅 Tomato Plant Stage Prediction using Deep Learning

## 📌 Project Overview
This project aims to automate the **identification of tomato plant growth stages** using deep learning. The model classifies tomato plants into two stages:
- **Stage 1: Early Vegetative**
- **Stage 2: Flowering Initiation**

### 🔬 Deep Learning Models Used:
- **Custom CNN**
- **ResNet50**
- **VGG16**
- **InceptionV3**
- **EfficientNetB0**
- **MobileNetV2**
- **YOLOv3**

The best-performing models were **ResNet50** and **EfficientNetB0**, achieving high accuracy.

---

## 📂 Dataset
The dataset contains **500 images** of tomato plants at different growth stages. It was collected from **Tamil Nadu Agricultural University (TNAU)**.

🔗 **Dataset Link:** [Tomato Plant Stages Dataset on Kaggle](https://www.kaggle.com/datasets/arjunsudheer326/tomato-plant-stages-dataset)

---

## ⚙️ Installation & Usage
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Tomato-Plant-Stage-Prediction.git
cd Tomato-Plant-Stage-Prediction
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
Launch Jupyter Notebook and open `miniproject.ipynb`.
```bash
jupyter notebook
```

---

## 📊 Model Performance
| Model | Accuracy |
|--------|------------|
| **ResNet50** | 97.75% |
| **EfficientNetB0** | 98.87% |
| **VGG16** | 98.87% |
| **Custom CNN** | 92.13% |

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Scikit-learn**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🚀 Future Scope
- Improve model generalization under different environmental conditions.
- Deploy the model as a **web app using Flask or Streamlit**.
- Expand dataset with more diverse images.


## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify it.

🎯 **Star this repository ⭐ if you found it useful!**

