# Titanic & Iris Data Preprocessing and Exploratory Data Analysis (EDA)

## 📌 Overview

This project demonstrates the complete data preprocessing and exploratory data analysis (EDA) workflow on two popular machine learning datasets: **Titanic** and **Iris**. The goal is to clean the datasets, visualize patterns, analyze relationships between features, and prepare the data for machine learning models.

---

## 📂 Datasets

### Titanic Dataset
The Titanic dataset contains passenger information such as age, gender, passenger class, fare, and survival status. It is commonly used for binary classification tasks.

### Iris Dataset
The Iris dataset contains measurements of iris flowers, including sepal and petal dimensions, along with their species. It is widely used for multiclass classification.

---

## ⚙️ Preprocessing Performed

### Titanic
- Inspected dataset structure and summary statistics
- Handled missing values
- Removed unnecessary columns (`PassengerId`, `Name`, `Ticket`, `Cabin`)
- Encoded categorical features (`Sex`, `Embarked`)
- Standardized numerical features (`Age`, `Fare`)

### Iris
- Removed the `Id` column
- Encoded the `Species` column
- Standardized numerical features

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

- Histograms
- Boxplots
- Scatter plots
- Count plots
- Correlation matrix
- Correlation heatmap

These visualizations were used to examine:
- Data distributions
- Outliers
- Feature relationships
- Class distributions
- Correlations between variables

---

## 🔍 Key Insights

### Titanic
- Female passengers had a higher survival rate than males.
- First-class passengers were more likely to survive.
- Higher fares were associated with better survival chances.
- Fare distribution is highly right-skewed with several outliers.
- PassengerId has no predictive value and was removed.

### Iris
- Petal Length and Petal Width have a very strong positive correlation.
- Setosa is clearly separable from the other two species.
- Versicolor and Virginica show slight overlap.
- Petal measurements are the most informative features for classification.
- The dataset contains no missing values.

---

## 🤖 Machine Learning Readiness

After preprocessing, both datasets are clean and ready for machine learning models, including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---



---

---

## 📜 License

This project is created for educational and learning purposes.
