# Customer Churn Prediction

This project focuses on predicting customer churn using supervised machine learning models. The goal is to identify customers who are likely to leave a service and analyze key factors contributing to their decision.

## 📁 Project Structure
customer-churn-prediction/
│
├── data/ # Raw dataset
│ └── customer_churn.csv
│
├── notebooks/ # Notebooks for EDA and model building
│ └── 01_data_cleaning_and_eda_churn.ipynb
│
├── outputs/ # Charts, model evaluation results
│ ├── charts/
│ │ └── roc_curve.png
│ └── model_comparison.csv
│
├── README.md
└── requirements.txt # (Optional) Python dependencies


## 🚀 Project Goals

- Perform exploratory data analysis (EDA) to understand customer behavior
- Preprocess the data for modeling
- Train multiple classification models
- Compare model performance using metrics like Accuracy, Precision, Recall, and ROC Curve
- Export results for dashboarding and analysis

## 📊 Models Used

- Logistic Regression
- Random Forest Classifier

> You can easily extend this project by trying advanced models like XGBoost or SVM.

## 📈 Evaluation Metrics

The models are evaluated based on:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve (visualized in `outputs/charts/roc_curve.png`)

## 📦 Output

- 📊 `outputs/model_comparison.csv`: Summary of model performance
- 📉 `outputs/charts/roc_curve.png`: ROC curve comparing models

## 🛠️ Tech Stack

- Python (pandas, seaborn, scikit-learn, matplotlib)
- Jupyter / Google Colab
- Git + GitHub for version control

## 📌 How to Run

1. Clone the repository
2. Open the notebook `01_data_cleaning_and_eda_churn.ipynb`
3. Make sure your dataset is in the `data/` folder
4. Run all cells to perform EDA, train models, and generate output

## 💡 Future Improvements

- Hyperparameter tuning
- Include more models (XGBoost, LightGBM)
- Build a dashboard using Power BI or Streamlit
- Automate retraining and data updates

## 📬 Contact

Created by [Om Mahajan](https://github.com/mahajanom10)
mail - mahajanom1121@gmail.com
For feedback, feel free to open an issue or reach out on GitHub.






