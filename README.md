# 💳 Credit Card Fraud Detection

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to analyze transaction data, perform preprocessing and exploratory data analysis (EDA), and build a classification model that can distinguish between legitimate and fraudulent transactions.

---

## 🚀 Features

* Data preprocessing and cleaning
* Handling missing values
* Feature engineering and encoding categorical variables
* Exploratory Data Analysis (EDA) with visualizations
* Machine Learning model training using Support Vector Machine (SVM)
* Model evaluation

---

## 🗂️ Dataset

The dataset used in this project contains transaction details such as:

* Transaction time
* Merchant information
* Category of transaction
* Gender
* Fraud label (`is_fraud`)

> Note: The dataset file path used in the notebook:

```
fraudTrain.csv/fraudTrain.csv
```

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 1. Data Loading

* Read the dataset using Pandas
* Initial inspection using `.info()`, `.describe()`, `.dtypes()`

### 2. Data Preprocessing

* Convert date columns to datetime format
* Drop unnecessary columns (e.g., personal and irrelevant identifiers)
* Handle missing values using `dropna()`
* Encode categorical features using Label Encoding

### 3. Exploratory Data Analysis (EDA)

* Analyze fraud vs non-fraud distribution
* Visualize data using pie charts and other plots

### 4. Model Training

* Split features (`X`) and target (`Y`)
* Train a **Support Vector Classifier (SVC)** model

### 5. Model Evaluation

* Evaluate model performance using accuracy score

---

## 📊 Results

* The model is trained using SVM
* Accuracy is computed on the training dataset
* Further improvements can be made using:

  * Train-test split
  * Cross-validation
  * Advanced models (Random Forest, XGBoost, etc.)

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the project directory:

```
cd your-repo-name
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the Jupyter Notebook:

```
jupyter notebook
```

---

## 📌 Future Improvements

* Implement train-test split for better evaluation
* Handle class imbalance using SMOTE or undersampling
* Try advanced ML/DL models
* Deploy as a web application

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Archishman Hazra**

---

⭐ If you found this project useful, don't forget to star the repo!
