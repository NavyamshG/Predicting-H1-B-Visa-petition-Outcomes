# 🛂 Predicting H1B Visa Petition Outcomes

A data-driven classification project to predict the outcomes of H1B visa petitions based on historical application data. This project applies machine learning models to identify key factors contributing to visa approvals or denials.

---

## 🔍 Project Overview

This project explores patterns in H1B visa applications to predict whether a petition will be **certified** or **denied**. The focus is on preprocessing real-world datasets and applying classification models for predictive insights.

### Key outcomes include:

- **Data Cleaning & Preprocessing**: Handling missing values, encoding categorical features, feature scaling
- **Exploratory Data Analysis (EDA)**: Understanding application trends by year, employer, and job category
- **Modeling**: Applying logistic regression, decision trees, and random forest classifiers
- **Evaluation**: Using accuracy, precision, recall, F1-score, and confusion matrices to assess performance

---

## 📦 Prerequisites

Ensure you have Python installed along with the following libraries:

- `pandas`: For data manipulation
- `numpy`: For numerical computation
- `matplotlib`, `seaborn`: For data visualization
- `scikit-learn`: For model building and evaluation

---

## 📂 Project Structure

### Data Preprocessing  
- Encode categorical variables (like job title, location, employer name)  
- Remove duplicates and handle missing values  
- Balance the dataset if required using techniques like SMOTE  

### Machine Learning Models  
- Train-test split (typically 80-20)  
- Fit models: Logistic Regression, Decision Tree, Random Forest  
- Evaluate using classification metrics  

---

## 🚀 Steps to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/h1b-visa-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd h1b-visa-prediction
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Predicting_H1_B_Visa_petition_Outcomes.ipynb
   ```

---

## 🖼️ Visualization

The project includes visualizations such as:

- Bar charts for top employers and job categories  
- Pie charts showing distribution of application status  
- Confusion matrices to evaluate classifier performance  

---

## 📊 Key Features

- Real-world H1B visa petition dataset  
- Classification models to predict outcomes  
- Insightful visualizations of the U.S. work visa landscape  
- End-to-end ML pipeline from data cleaning to evaluation  

---

## 🤝 Conclusion

This project helps uncover trends and patterns in U.S. H1B visa processing using historical data and offers a predictive lens for future applications. It’s a practical implementation of machine learning in immigration policy analytics.
