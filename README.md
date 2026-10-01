# Data-Cleaning-Preprocessing
# Task 1: Data Cleaning & Preprocessing

## 📌 Objective

The objective of this task is to learn how to clean, preprocess, and prepare raw data for Machine Learning and Data Analysis.

In this project, the **Titanic dataset** is explored and processed using Python-based data science libraries.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Dataset

The project uses the **Titanic dataset**, which contains information about passengers such as:

- Passenger ID
- Passenger Class
- Name
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Cabin
- Port of Embarkation
- Survival status

---

## 🔍 Tasks Performed

### 1. Data Import & Exploration

- Imported the Titanic dataset using Pandas.
- Examined the first few rows of the dataset.
- Checked the shape of the dataset.
- Inspected column names and data types.
- Identified missing values.

### 2. Handling Missing Values

Missing values were identified and handled using appropriate preprocessing techniques.

Examples include:

- Filling numerical missing values using median/mean.
- Handling missing categorical values.
- Removing unnecessary columns where appropriate.

### 3. Categorical Data Encoding

Categorical features were converted into numerical representations so that they can be used by Machine Learning algorithms.

Examples:

- Encoding `Sex`
- Encoding `Embarked`
- Converting categorical values into numerical values.

### 4. Feature Scaling

Numerical features were normalized/standardized to bring them to a suitable scale for Machine Learning algorithms.

Features such as:

- Age
- Fare

were considered during preprocessing.

### 5. Outlier Detection & Removal

Outliers were visualized using **boxplots** with Matplotlib/Seaborn.

The following numerical features were analyzed for potential outliers:

- Age
- Fare

Extreme values were identified and removed using an appropriate outlier detection method.

---

## 📊 Data Visualization

Seaborn and Matplotlib were used to visualize the dataset and understand its distribution.

Visualizations include:

- Boxplots
- Distribution plots
- Data exploration charts

These visualizations helped identify unusual values and understand the structure of the data.

---

## 📁 Project Structure

```text
Task-1-Data-Cleaning-Preprocessing/
│
├── DATA/
│   ├── Titanic-Dataset.csv
│   ├── cleaned_titanic.csv
│   └── enspec.ipynb
│
├── .gitignore
└── README.md