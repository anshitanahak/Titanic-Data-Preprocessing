# Titanic Data Cleaning & Preprocessing 🚢

## 📌 Internship Task 1 – AI & ML

### 🎯 Objective
The objective of this task is to clean and preprocess raw data to make it suitable for Machine Learning models.

Dataset used: Titanic Survival Prediction Dataset

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset Information

The Titanic dataset contains information about passengers such as:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

---

## 🔍 Steps Performed

### 1️⃣ Data Exploration
- Checked dataset structure using `.info()`
- Checked statistical summary using `.describe()`
- Identified missing values using `.isnull().sum()`

---

### 2️⃣ Handling Missing Values
- Filled missing `Age` values using median.
- Filled missing `Embarked` values using mode.
- Dropped `Cabin` column due to excessive missing values.

---

### 3️⃣ Encoding Categorical Variables
- Converted `Sex` column using binary encoding (male = 0, female = 1).
- Applied One-Hot Encoding on `Embarked` column.

---

### 4️⃣ Feature Scaling
- Applied StandardScaler to normalize `Age` and `Fare`.

---

### 5️⃣ Outlier Detection & Removal
- Visualized outliers using boxplot.
- Removed outliers using IQR (Interquartile Range) method.

---

## ✅ Final Result
The dataset is now:
- Cleaned
- Encoded
- Scaled
- Free from major outliers
- Ready for Machine Learning model training

---

## 📊 Conclusion
Data preprocessing is a crucial step in Machine Learning as it improves model performance and ensures accurate predictions.

---

## 👩‍💻 Author
Anshita Tanaya Nahak  
AI & ML Internship Task Submission
