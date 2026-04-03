{
  "title": "Credit Card Fraud Detection",
  "emoji": "💳",
  "overview": "This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It analyzes transaction data, performs preprocessing and EDA, and builds a classification model to distinguish between legitimate and fraudulent transactions.",
  "features": [
    "Data preprocessing and cleaning",
    "Handling missing values",
    "Feature engineering and encoding categorical variables",
    "Exploratory Data Analysis (EDA) with visualizations",
    "Machine Learning model training using Support Vector Machine (SVM)",
    "Model evaluation"
  ],
  "dataset": {
    "description": "Contains transaction details such as time, merchant info, category, gender, and fraud label.",
    "fields": [
      "Transaction time",
      "Merchant information",
      "Category of transaction",
      "Gender",
      "is_fraud (target label)"
    ],
    "path": "fraudTrain.csv/fraudTrain.csv"
  },
  "tech_stack": [
    "Python",
    "NumPy",
    "Pandas",
    "Matplotlib",
    "Seaborn",
    "Scikit-learn"
  ],
  "workflow": {
    "data_loading": [
      "Load dataset using Pandas",
      "Inspect using info(), describe(), dtypes()"
    ],
    "data_preprocessing": [
      "Convert date columns to datetime",
      "Drop unnecessary columns",
      "Handle missing values",
      "Encode categorical features"
    ],
    "eda": [
      "Analyze fraud vs non-fraud distribution",
      "Visualize using charts"
    ],
    "model_training": [
      "Split features and target",
      "Train SVM classifier"
    ],
    "model_evaluation": [
      "Evaluate using accuracy score"
    ]
  },
  "results": {
    "model": "Support Vector Machine (SVM)",
    "notes": [
      "Accuracy calculated on training data",
      "Can be improved with better validation and advanced models"
    ]
  },
  "setup": {
    "steps": [
      "git clone https://github.com/your-username/your-repo-name.git",
      "cd your-repo-name",
      "pip install -r requirements.txt",
      "jupyter notebook"
    ]
  },
  "future_improvements": [
    "Implement train-test split",
    "Handle class imbalance (SMOTE, undersampling)",
    "Try advanced models (Random Forest, XGBoost)",
    "Deploy as a web application"
  ],
  "contributing": "Fork the repo and submit a pull request.",
  "license": "MIT",
  "author": "Archishman Hazra"
}
