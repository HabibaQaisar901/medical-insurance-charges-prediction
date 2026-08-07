# Medical Insurance Charges Prediction

A Machine Learning project that predicts individual medical insurance charges using demographic and lifestyle factors. This project demonstrates the complete machine learning workflow, from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and prediction.

---

# Project Overview

Medical insurance costs vary significantly depending on factors such as age, BMI, smoking status, region, and the number of children. The objective of this project is to develop a regression model capable of accurately predicting medical insurance charges based on these features.

This project was developed using the **Medical Insurance Charges** dataset from Kaggle as part of my AI & Machine Learning learning journey.

---

# Problem Statement

Healthcare insurance costs are influenced by multiple demographic and lifestyle factors. Predicting these costs accurately can help insurance companies estimate premiums more effectively and assist individuals in understanding the factors affecting their insurance expenses.

---

# Objectives

- Understand the medical insurance dataset
- Perform data cleaning and preprocessing
- Explore relationships between different variables
- Perform Exploratory Data Analysis (EDA)
- Build and train a regression model
- Evaluate model performance using standard metrics
- Predict insurance charges for unseen data

---

# Dataset

**Source:** Kaggle – Medical Insurance Charges Dataset

**Dataset Link:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

### Features

- Age
- Sex
- BMI
- Number of Children
- Smoker Status
- Region

**Target Variable**

- Insurance Charges

---

# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Machine Learning Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning & Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Prediction
10. Conclusion

---

# Machine Learning Model

A regression model was developed using Scikit-learn to predict medical insurance charges based on patient information.

---

# Model Performance

The trained model achieved the following performance:

| Metric | Value |
|---------|-------|
| R² Score | **0.86** |
| RMSE | **Approximately \$4,598** |
| MAE | **Approximately \$2,347** |

These results indicate that the model explains approximately **86% of the variance** in medical insurance charges while maintaining a reasonable prediction error.

---

# Key Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature encoding
- Regression model development
- Model evaluation
- Insurance charge prediction

---

# Repository Structure

```
medical-insurance-charges-prediction/
│
├── Medical_Insurance_Charges.ipynb
├── Project_Report.pdf
├── Project_Presentation.pdf
├── Data_Profiling_Report.html
└── README.md
```

---

# Project Files

- **Medical_Insurance_Charges.ipynb** — Google Colab Notebook containing the complete implementation.
- **Project_Report.pdf** — Detailed project documentation.
- **Project_Presentation.pdf** — Presentation summarizing the project.
- **Data_Profiling_Report.html** — Automated exploratory data analysis report.
- **README.md** — Project documentation.

---

# How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook using Google Colab or Jupyter Notebook.
4. Run the notebook cells sequentially.
5. Review the generated predictions and evaluation metrics.

---

# Future Improvements

- Hyperparameter tuning
- Feature engineering
- Testing additional regression algorithms
- Model deployment using Streamlit or Flask
- Building an interactive web application

---

# Acknowledgements

- Kaggle for providing the dataset.
- Google Colab for the development environment.
- Scikit-learn for machine learning tools and documentation.

---

# Author

**Habiba Qaiser**

**BS Mathematics Student**

**AI & Machine Learning Enthusiast**

LinkedIn: (https://www.linkedin.com/in/habiba-qaisar-75a3ba421)

GitHub: (https://github.com/HabibaQaisar901
License

This project is licensed under the MIT License.
