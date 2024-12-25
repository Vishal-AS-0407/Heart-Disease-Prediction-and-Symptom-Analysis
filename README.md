# Heart Disease Prediction and Symptom Analysis

This project is a machine learning-based system designed to predict the likelihood of heart disease and analyze symptoms for further validation. The primary model used is Random Forest, which demonstrated the highest accuracy (90.16%) among all tested models.

---

## Features

- **Heart Disease Prediction**: Predicts whether the user is likely to have heart disease based on provided health parameters.
- **Symptom Analysis**: If heart disease is predicted, the system asks follow-up questions about common symptoms to confirm or refine the prediction.
- **Interactive User Input**: Collects user data interactively through prompts.

---

## Dataset

- **Source**: `heart.csv`
- **Description**: The dataset includes features relevant to heart disease, such as age, cholesterol levels, blood pressure, and more. The target column indicates the presence (1) or absence (0) of heart disease.

---

## Model Development

### Steps:
1. **Data Visualization and Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions and correlations.
   - Identified important features for prediction.
2. **Model Training**:
   - Trained the following models:
     - Logistic Regression
     - Naive Bayes
     - Decision Tree
     - Random Forest
     - Support Vector Machine (SVM)
     - K-Nearest Neighbors (KNN)
   - **Best Model**: Random Forest with 90.16% accuracy.
3. **Inference Model**:
   - Developed a user-interactive prediction model using Random Forest.

---

## Installation and Usage

### Prerequisites
- Python 3.8 or later
- Required libraries: `pandas`, `scikit-learn`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Model
1. Ensure the dataset `heart.csv` is in the project directory.
2. Execute the Final Kernal in the notebook
3. Follow the prompts to input health parameters.
4. If heart disease is predicted, proceed with the symptom analysis for further insights.

---

## How It Works

1. **Prediction**:
   - The model predicts heart disease based on user inputs.
   - Example inputs: age, cholesterol levels, blood pressure, etc.
2. **Symptom Analysis**:
   - If heart disease is predicted, the system asks yes/no questions about common symptoms.
   - If more than half of the symptoms are present, the system advises consulting a healthcare professional.
---
### 🌟 **Show Your Support!**  

If you find this project helpful, give it a ⭐ on GitHub and share it with others! 😊 
