# Cervical Cancer Prediction Using Machine Learning

## Introduction
Cervical cancer is one of the most common cancers in women, primarily caused by a persistent infection with high-risk Human Papillomavirus (HPV).  
It develops slowly and often shows no symptoms in its early stages. Therefore, early detection of cervical cancer is crucial for effective treatment and reduced mortality.

This project applies machine learning algorithms to analyze patient data and predict the likelihood of cervical cancer based on diagnostic test results.

---

## Approaches Used
This project uses approach for detecting cervical cancer:

* **Clinical Data Analysis** – Identifying patterns in patient medical records.

The focus is on improving diagnostic reliability by analyzing the relationships among multiple clinical factors.

---

## Dataset

The dataset includes patient attributes and diagnostic results.

### Features:
- Age  
- Number of sexual partners  
- First sexual intercourse age  
- Number of pregnancies  
- Smoking habits (years, packs/year)  
- Hormonal contraceptive use (years)  
- IUD usage (years)  
- STDs and related conditions  
- HPV infection status  

### Target Variables (Diagnosis Methods):
Cervical cancer can be diagnosed using four main clinical methods:
- **Hinselmann**  
- **Schiller**  
- **Citology**  
- **Biopsy**

Each of these columns is used individually as a dependent variable for predictive analysis.

---

## Tech Stack

**Programming Language:** Python  

**Libraries Used:**
- numpy, pandas → Data processing  
- matplotlib, seaborn → Data visualization  
- scikit-learn → Model training and evaluation

---

## Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- Support Vector Machine (SVM)  
- Naive Bayes Classifier  
- K-Nearest Neighbors (KNN)  

---

## Model Evaluation

- Train-Test Split (80-20)   
Each diagnostic method (Hinselmann, Schiller, Citology, Biopsy) was analyzed separately to determine model effectiveness.

- Accuracy Results

| Diagnosis Method | Accuracy (%) |
|------------------|--------------|
| Biopsy           | **96.41%**   |
| Hinselmann       | 95.21%       |
| Citology         | 95.21%       |
| Schiller         | 89.22%       |

---

## Conclusion
- The **Biopsy method** achieved the highest predictive accuracy (96.41%), making it the most reliable target variable for diagnosis modeling.  
- The **Hinselmann** and **Citology** methods also showed high accuracy (95.21%), proving to be effective alternatives.  
- The **Schiller** method recorded the lowest accuracy (89.22%), indicating limited performance in certain predictive contexts.  

Therefore, using the **Biopsy method** as the target variable is recommended for achieving optimal diagnostic performance in cervical cancer prediction.

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/shubhangi115/Cervical_Cancer_Prediction.git

# Navigate to the project folder
cd Cervical_Cancer_Prediction

# Run the Jupyter Notebook or Python script
jupyter notebook
