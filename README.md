# Predicting Chronic Diseases Using Machine Learning

## Abstract

This study focuses on predicting chronic diseases such as asthma, diabetes, and brain stroke using advanced machine learning algorithms. The models implemented include **Random Forest**, **XGBoost**, and **Neural Networks**, which are robust in modeling complex patterns. Preprocessing techniques like feature scaling, SMOTE for balancing, and feature engineering were applied to improve model performance. Each algorithm was fine-tuned to optimize accuracy, precision, and recall. Results show that **Random Forest** and **XGBoost** performed exceptionally well across most datasets, while **Neural Networks** effectively captured intricate relationships among features. Key risk factors such as age, BMI, and glucose levels were identified, highlighting the reliability and practical applicability of these models in healthcare. Future work includes exploring more advanced designs, diverse datasets, and real-time applications.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Analysis Highlights](#analysis-highlights)
6. [Contributing](#contributing)
7. [License](#license)

---

## Introduction

Chronic diseases such as asthma, diabetes, and brain stroke are among the leading causes of death and disability worldwide, accounting for approximately **74% of global deaths** according to the World Health Organization. These diseases are influenced by genetic, environmental, and lifestyle factors, making early detection and management critical. 

Machine learning and artificial intelligence offer promising solutions for predicting and managing chronic diseases. By leveraging large volumes of data from electronic health records and wearable devices, these tools can uncover hidden trends and patterns, enabling quicker and more accurate diagnoses. This project explores the predictive capabilities of **Random Forest**, **XGBoost**, and **Neural Networks** in identifying chronic diseases and evaluates their performance using metrics like accuracy, precision, recall, and F1-score.

---

## Features

This project includes the following features:
- **Data Preprocessing**: Techniques such as feature scaling, SMOTE for balancing, and feature engineering.
- **Advanced Algorithms**:
  - **Random Forest**: Ensemble of decision trees for stable predictions.
  - **XGBoost**: Gradient boosting method for high-performance predictions.
  - **Neural Networks**: Deep learning models for capturing complex relationships.
- **Evaluation Metrics**: Accuracy, precision, recall, and F1-score for performance assessment.
- **Key Risk Factors**: Identification of factors like age, BMI, and glucose levels influencing disease prediction.

---

## Installation

To run this project locally, follow these steps:

### Prerequisites
- Install [Python](https://www.python.org/) (preferably Python 3.8 or higher).
- Ensure you have Git installed: [Git Downloads](https://git-scm.com/downloads).

### Clone the Repository
```bash
git clone https://github.com/your-username/chronic-disease-prediction.git
cd chronic-disease-prediction
```

### Install Required Libraries
Run the following commands in your terminal to install the necessary libraries:
```bash
pip install numpy pandas scikit-learn xgboost tensorflow imbalanced-learn
```

### Load the Dataset
Place the dataset files (e.g., `asthma.csv`, `diabetes.csv`, `stroke.csv`) in the root directory of the project. Ensure the file paths match those specified in the script.

---

## Usage

1. Open the Python script (`predictive_model.py`) in your preferred IDE.
2. Set the working directory to the project folder:
   ```python
   import os
   os.chdir("path/to/chronic-disease-prediction")
   ```
3. Run the script step-by-step to preprocess the data, train the models, and evaluate their performance.
4. Explore the outputs:
   - Model performance metrics (accuracy, precision, recall, F1-score).
   - Feature importance plots.
   - Risk factor analysis.

---

## Analysis Highlights

### Key Findings
1. **Random Forest**:
   - Achieved high precision and recall across datasets.
   - Handles heterogeneous and complex data effectively.
2. **XGBoost**:
   - Demonstrated superior performance on large datasets.
   - Particularly effective in accurately estimating risk factors.
3. **Neural Networks**:
   - Captured intricate relationships among features.
   - Provided insights into non-linear patterns in the data.
4. **Risk Factors**:
   - Age, BMI, and glucose levels were identified as significant predictors of chronic diseases.

### Examples
- **Dataset**: Diabetes Prediction  
  - Key Features: Glucose levels, BMI, age.
  - Model Performance: Random Forest achieved **92% accuracy**, XGBoost achieved **91% accuracy**, and Neural Networks achieved **89% accuracy**.
- **Dataset**: Stroke Prediction  
  - Key Features: Blood pressure, lifestyle habits.
  - Model Performance: XGBoost outperformed other models with an **F1-score of 0.87**.

---

## Contributing

We welcome contributions to this project! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

For major changes, please open an issue first to discuss your ideas.

---


## Acknowledgments

- Thanks to the creators of the Python libraries used in this project.
- Special thanks to the contributors of the chronic disease datasets for making this analysis possible.
