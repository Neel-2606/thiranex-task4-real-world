# 🌍 Real-world Data Project

## 🎯 Objective
This project is part of the **Thiranex Data Science Internship** (Task 4). The objective is to apply all previously learned data science skills (cleaning, EDA, and predictive modeling) into a comprehensive, end-to-end pipeline in a real-world context.

## 📊 Dataset Description
For this domain-specific applied project, we utilized the **Heart Disease Dataset** from the health sector. The dataset contains various clinical and non-clinical features (such as age, sex, chest pain type, resting blood pressure, cholesterol levels, etc.) used to predict the presence of heart disease in patients. 

## 🛠️ Key Features & Methodology
1. **Exploratory Data Analysis (EDA):**
   - Visualized the target variable distribution (Heart Disease vs No Heart Disease) to check for class imbalances.
   - Plotted a full feature correlation heatmap to find multi-collinearity and relationships between clinical attributes and the target variable.
2. **Data Preprocessing:**
   - Separated the independent variables (`X`) and the dependent target (`y`).
   - Performed an 80-20 Train-Test split.
   - Applied **StandardScaler** to normalize the clinical features, ensuring gradient algorithms and distance metrics function optimally.
3. **Model Training & Prediction:**
   - Deployed a **Random Forest Classifier** (`n_estimators=100`) as the core predictive model on the scaled training data.
   - Generated predictions on the unseen test set.
4. **Evaluation & Interpretation:**
   - Evaluated the model using overall Accuracy and a comprehensive Classification Report.
   - Extracted and visualized **Feature Importances**, providing real-world clinical insight into which health metrics most strongly dictate the presence of heart disease.

## 📈 Expected Outcome Achieved
Successfully applied data science skills in a real-world health context. Demonstrated the ability to take raw, unscaled domain data and process it into a highly interpretable, actionable machine learning model with visualized conclusions.

## 💻 Technologies Used
- **Python 3.10**
- **Scikit-Learn** (Standardization, Random Forest, Metrics)
- **Pandas & NumPy** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization & Feature Importance plotting)

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/real_world_analysis.ipynb
   ```
4. Run all cells sequentially to view the full data pipeline from EDA to Machine Learning evaluation.
