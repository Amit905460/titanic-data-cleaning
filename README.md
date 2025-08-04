# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 🧠 AI & ML Internship Task 1

### 📌 Objective:
To clean and preprocess raw data to make it suitable for Machine Learning models.

---

## 📁 Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Files Used:** `titanic.csv`

---

## 🛠 Tools & Libraries Used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Steps Performed:

### 1. Data Loading & Exploration
- Loaded the Titanic dataset using Pandas.
- Explored dataset structure with `.info()`, `.describe()`, `.head()`.

### 2. Handling Missing Values
- Filled missing values in:
  - `Age` using **mean**
  - `Embarked` using **mode**
  - Dropped `Cabin` due to too many missing values.

### 3. Encoding Categorical Features
- Used **Label Encoding** and **One-Hot Encoding** on `Sex`, `Embarked`, and `Pclass`.

### 4. Feature Scaling
- Applied **MinMaxScaler** to normalize numerical features like `Age`, `Fare`.

### 5. Outlier Detection & Removal
- Plotted **boxplots** for `Fare` and `Age`.
- Detected and removed outliers based on visual inspection and IQR method.

---

## 📊 Visualizations:
- Correlation Heatmap
- Boxplots for outlier detection
- Countplot for survival distribution

---

## 📌 Outcome:
- Cleaned and preprocessed dataset is now ready for ML model training.
- Understood key preprocessing techniques like handling nulls, encoding, normalization, and outlier removal.

---

## ▶️ How to Run
1. Clone the repo:
   ```
   git clone https://github.com/Amit905460/titanic-data-cleaning
   ```
2. Open the notebook `Data Cleaning & Preprocessing.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells step by step.

---

## 🔗 Submission
- Task completed for AI & ML Internship.
- GitHub Repository: [https://github.com/Amit905460/titanic-data-cleaning](https://github.com/Amit905460/titanic-data-cleaning)
