# 🧠 Brain Tumor Classification Using Deep Learning & Grad-CAM

This project focuses on classifying brain tumors from MRI images using **Deep Learning (CNNs)** and interpreting model predictions with **Grad-CAM (Gradient-weighted Class Activation Mapping)**.  
It aims to assist in medical diagnostics by making AI models more **explainable**.

---

## 📌 Project Overview
- Built a **CNN model** using TensorFlow/Keras.  
- Applied **Grad-CAM** to highlight regions of MRI scans influencing predictions.  
- Provides insights into tumor localization, improving interpretability.  

---

## 📂 Repository Structure
```
├── Brain_Tumor_Classification_Using_DL_&_GradCAM.ipynb   # Main Jupyter Notebook
├── requirements.txt                                      # Dependencies
├── README.md                                             # Project Documentation
└── data/                                                 # Place dataset here
```

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install Dependencies
Install all required Python libraries:
```bash
pip install -r requirements.txt
```

### 3️⃣ Download Dataset
The dataset can be obtained from Kaggle:  
🔗 [Brain Tumor MRI Dataset – Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)

After downloading, place it inside the `data/` folder.

### 4️⃣ Run the Notebook
```bash
jupyter notebook Brain_Tumor_Classification_Using_DL_&_GradCAM.ipynb
```

---

## 📊 Grad-CAM Visualizations
Grad-CAM helps in **visualizing** which regions of MRI images influence the model’s predictions, enabling better explainability in medical AI systems.

---

## 📈 Results
- Achieved high classification accuracy on MRI scans.  
- Grad-CAM highlighted tumor-affected regions effectively.  

---

## ⚙️ Requirements
The project requires the following Python libraries (see `requirements.txt` for details):  
- TensorFlow  
- scikit-learn  
- scikit-image  
- OpenCV  
- Seaborn  
- Matplotlib  
- Pandas  
- Pillow  
- imutils  
- opendatasets  

---

## ✨ Acknowledgement
Dataset provided by **Masoud Nickparvar** on Kaggle.  
🔗 [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)
