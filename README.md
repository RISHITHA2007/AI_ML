# AI_ML
# 🎓 Student Data Analysis Project

## 📌 Overview

This project focuses on **explatory data analysis (EDA)** of a student dataset to uncover patterns, trends, and relationships between various attributes such as skills, interests, and future career goals.

The analysis is performed using Python libraries like **Pandas, Matplotlib, and Seaborn** in a Jupyter Notebook.

---

## 📂 Dataset

The dataset contains information about students, including:

* Gender
* Age
* Interested Domain
* Programming Skills (Python, SQL, Java)
* Number of Projects
* Future Career

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib
* Seaborn
* TensorFlow (imported, not heavily used)

---
🤖 Model / Algorithm Used

A Neural Network (Deep Learning model) was implemented using TensorFlow/Keras.

Model evaluation:

test_mse_score = model.evaluate(test_data, test_targets)
Performance metric:
Mean Squared Error (MSE)

## 🔍 Project Workflow

### 1. Data Loading

* Dataset is loaded using Pandas from a CSV file.

### 2. Data Cleaning

* Checked for missing values
* Removed unnecessary columns (e.g., Student ID, Name, Major)
* Checked for duplicates

### 3. Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

* 📊 Gender distribution (bar chart & pie chart)
* 📊 Interested domain distribution
* 📊 Programming skills distribution (Python, SQL, Java)
* 📊 Number of projects analysis
* 📊 Age distribution
* 📊 Future career trends

### 4. Relationship Analysis

* 📈 Future Career vs Interested Domain (stacked bar chart)
* 🔥 Future Career vs Projects (heatmap)

5. Model Training

Trained the model on training dataset using:

model.fit(train_data, train_targets)
6. Model Evaluation

Tested the model on unseen data:

test_mse_score = model.evaluate(test_data, test_targets)
Evaluated performance using MSE

---

## 📊 Key Insights

* Distribution of students across different domains and skills
* Popular career choices among students
* Relationship between skills/projects and career goals

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the notebook:

   ```bash
   jupyter notebook Micro_Project.ipynb
   ```

3. Run all cells to reproduce the analysis.

---

## 📁 Project Structure

```
├── Micro_Project.ipynb   # Main notebook
├── cs_students.csv      # Dataset
└── README.md            # Project documentation
```

---

## 🚀 Future Improvements

* Add machine learning models for prediction
* Improve data preprocessing
* Add interactive dashboards (Plotly / Power BI)

---

## 🤝 Contributing

Feel free to fork this repository and contribute by submitting a pull request.

---


