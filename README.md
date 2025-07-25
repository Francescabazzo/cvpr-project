# Project 2 - Bag of Words Classifier 

_Project for the Computer Vision and Pattern Recognition Exam_

---

## Description 

This project implements an image classification system based on the Bag-of-Words (BoW) model using SIFT features. It supports both K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) classifiers, including a variant with a custom χ² kernel.

The dataset used consists of 15 scene categories and is already split into train/test folders.

---

## 📁 Project Structure

```
📦cvpr-project/
├── data/
│   ├── train 
│   └── test 
├── BoW_Classifier.ipynb         # Notebook with the implementation  
├── requirements.txt 
└── README.md
```

---

## ⚙️ Requirements 

You can install all dependencies via 

```
pip install -r requirements.txt
```

---

## 🚀 Usage 

### 1. Clone the repository 
```
git clone https://github.com/francescabazzo/cvpr-project.git
```

### 2. Install the requirements 
```
pip install -r requirements.txt
cd cvpr-project 
```

### 3. Run the pipeline 

To run the full pipeline, open the Jupiter notebook 
```
BoW_Classifier.ipynb
```

