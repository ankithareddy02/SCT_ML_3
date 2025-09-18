# 🐱🐶 Cats vs Dogs Classification using SVM

## 📌 Project Overview
This project applies a **Support Vector Machine (SVM)** classifier to distinguish between images of **cats** and **dogs**.  
The dataset used is the **Cats and Dogs filtered dataset** provided by TensorFlow.  
The goal is to build a simple machine learning pipeline for **image classification** using traditional ML methods.

---

## 📂 Project Structure
```
cats_dogs_svm/
├── data/
│   └── cats_and_dogs_filtered/        # Dataset (train/validation folders)
├── notebooks/
│   └── task3_cats_dogs_svm.ipynb      # Jupyter Notebook with code
├── README.md                          # Project documentation
├── requirements.txt                   # Dependencies
└── .gitignore                         # Ignore unnecessary files
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cats_dogs_svm.git
   cd cats_dogs_svm
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook notebooks/task3_cats_dogs_svm.ipynb
   ```

4. Run all cells → trains SVM and evaluates performance.

---

## 📊 Results
- **Accuracy:** ~75–85% depending on dataset split  
- **Outputs:**  
  - Classification Report (Precision, Recall, F1-Score)  
  - Confusion Matrix heatmap  
  - Custom function to predict new cat/dog images  

---

## 📜 License
This project is for educational purposes and demonstrates **image classification using Support Vector Machine (SVM)**.
