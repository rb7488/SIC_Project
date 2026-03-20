# 🚀 Adaptive Inference Engine for Human Activity Recognition

## 📌 Overview

This project focuses on building an **Adaptive Inference System** that dynamically selects between machine learning models based on prediction confidence.

The goal is to achieve **high accuracy while reducing computational cost**, making the system more efficient for real-world applications.

---

##  Problem Statement

Traditional machine learning systems use a single model for all predictions, which can either:

* Be **fast but less accurate**, or
* Be **accurate but computationally expensive**

This project solves this by introducing a **confidence-based model selection mechanism**.

---

##  Proposed Solution

The system uses two types of models:

* 🔹 **Lightweight Model:** Logistic Regression (fast inference)
* 🔹 **Complex Model:** Random Forest (higher accuracy)

### Key Idea

* If prediction confidence is **high** → use lightweight model
* If prediction confidence is **low** → switch to complex model

This creates a balance between **efficiency and performance**.

---

## Dataset

* **UCI Human Activity Recognition (HAR) Dataset**
* Contains smartphone sensor data (accelerometer + gyroscope)
* Activities include:

  * Walking
  * Sitting
  * Standing
  * Laying
  * Walking Upstairs
  * Walking Downstairs

---

##  Project Workflow

1. Data Collection and Loading
2. Data Preprocessing and Feature Scaling
3. Exploratory Data Analysis (EDA)
4. Model Training (Logistic Regression, Random Forest)
5. Confidence Score Extraction
6. Gating Mechanism (Adaptive Inference)
7. Performance Evaluation

---

##  Models Used

| Model               | Purpose                       |
| ------------------- | ----------------------------- |
| Logistic Regression | Fast predictions              |
| Random Forest       | High accuracy                 |
| Adaptive System     | Balance accuracy + efficiency |

---

##  Results

* Adaptive system achieved **accuracy close to Random Forest**
* Reduced unnecessary usage of complex model
* Improved **efficiency without compromising performance**

---

##  Key Concepts

* Confidence-based decision making
* Model uncertainty (Entropy)
* Adaptive inference systems
* Accuracy vs computational cost trade-off

---

## Tech Stack

* Python
* NumPy, Pandas
* Scikit-learn
* Matplotlib

---

##  Project Structure

```
Adaptive_Inference_Project/
│
├── data/
│
├── processed_data/
│
├── models/
│
├── notebooks/
│   ├── notebook_1_data_preprocessing.ipynb
│   ├── notebook_2_baseline_models.ipynb
│   ├── notebook_3_confidence_analysis.ipynb
│   ├── notebook_4_adaptive_inference.ipynb
│   └── notebook_5_evaluation.ipynb
│
├── outputs/
│
└── README.md
```

---

##  How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Open notebooks in Google Colab or Jupyter

3. Run notebooks in sequence:

* Notebook 1 → Data Processing
* Notebook 2 → Model Training
* Notebook 3 → Confidence Analysis
* Notebook 4 → Adaptive Inference
* Notebook 5 → Evaluation

---

##  Key Learnings

* Building AI systems is more than just training models
* Confidence plays a critical role in decision-making
* Adaptive systems improve real-world applicability

---

##  Future Improvements

* Use Deep Learning models (CNN / LSTM)
* Real-time activity recognition system
* Deployment using APIs

---

## Acknowledgement

This project was developed as part of the **Samsung Innovation Campus AI Program**, which provided hands-on experience in real-world AI applications.

---

## Connect with Me

If you found this project interesting or want to collaborate, feel free to connect!

