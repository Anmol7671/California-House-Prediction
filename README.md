California House Price Prediction 🏠

📌 Overview

This project focuses on building a machine learning model to predict house prices using structured housing data. The workflow includes data preprocessing, feature engineering, and model building using Python.

---

📂 Dataset

- File: "Gurgaon_housing.csv"
- The dataset contains various features related to housing such as location, size, and other relevant attributes used to predict house prices.

---

⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Handling Missing Values
  
  - Used Simple Imputer to fill missing data

- Encoding Categorical Variables
  
  - Applied One-Hot Encoding to convert categorical features into numerical form

- Feature Scaling
  
  - Used Standard Scaler to normalize numerical features

---

🤖 Model Building

- Built a machine learning model using Scikit-learn
- Applied preprocessing pipeline before training
- Model trained on processed dataset for price prediction

(Decision Tree Regressor is used in this Project)

---

📊 Workflow

1. Load dataset
2. Handle missing values
3. Encode categorical variables
4. Scale numerical features
5. Train model
6. Evaluate performance

---

🚀 How to Run the Project

1. Clone the repository:

git clone https://github.com/your-username/California-House-Prediction.git

2. Navigate to the project folder:

cd California-House-Prediction

3. Install dependencies:

pip install -r requirements.txt

4. Run the notebook:

jupyter notebook Predictor_Model.ipynb

---

📦 Requirements

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- jupyter

---

📈 Results

- Model performance depends on dataset quality and preprocessing
- (You should add metrics like RMSE, MAE, or R² here)

---

📌 Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Feature selection techniques
- Deploy as a web app

---

👨‍💻 Author

- Anmol Gupta

---

⭐ Acknowledgement

This project is created for learning and practicing machine learning concepts including data preprocessing and model building.
