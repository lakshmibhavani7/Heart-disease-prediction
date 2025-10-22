# Heart-disease-prediction
Predicting heart disease risk using machine learning (Logistic Regression).

# Heart Disease Prediction using Logistic Regression

## 📊 Project Overview
This project implements a machine learning model to predict the presence of heart disease in patients based on clinical parameters. Using logistic regression, the model analyzes 13 medical features to classify patients with 82% accuracy, demonstrating strong potential for medical screening applications.

## 🎯 Key Features
- **Comprehensive Data Analysis** with duplicate detection and data validation
- **Robust Preprocessing** including standardization and train-test splitting
- **Interpretable Machine Learning Model** with feature importance analysis
- **Multi-metric Evaluation** using accuracy, precision, and recall scores

## 📈 Model Performance
The trained logistic regression model achieved:
- **Accuracy**: 81.97%
- **Precision**: 75.76%
- **Recall**: 89.29%

The high recall score (89.29%) makes this model particularly effective for medical screening, as it excels at identifying true positive cases of heart disease.

## 🛠️ Technical Implementation

### Technologies Used
- **Python 3** with Google Colab
- **Machine Learning**: Scikit-learn (LogisticRegression, StandardScaler)
- **Data Analysis**: Pandas, NumPy
- **Model Evaluation**: Accuracy, Precision, Recall metrics

### Dataset
- **Source**: Heart Disease Dataset (UCI Machine Learning Repository)
- **Records**: 303 patient observations
- **Features**: 13 clinical parameters including age, sex, chest pain type, cholesterol levels, and more
- **Target**: Presence of heart disease (0 = no, 1 = yes)

### Methodology
1. **Data Preprocessing**: Handled duplicates, validated data types, no missing values
2. **Feature Scaling**: Applied StandardScaler for optimal model performance
3. **Model Training**: Implemented Logistic Regression with 80-20 train-test split
4. **Evaluation**: Comprehensive performance analysis with multiple metrics

## 🔍 Key Findings

### Top Predictive Features
The model identified these as the most significant predictors:
1. **Chest Pain Type (cp)**: Strong indicator of heart condition
2. **Maximum Heart Rate (thalach)**: Critical cardiovascular metric
3. **Number of Major Vessels (ca)**: Important anatomical factor

### Data Quality Insights
- **Clean Dataset**: No missing values requiring imputation
- **Minimal Preprocessing**: Only one duplicate record removed
- **Well-balanced**: Suitable for machine learning applications

## 💡 Business Applications
This model can assist healthcare professionals in:
- **Early Risk Detection**: Identifying patients at risk of heart disease
- **Clinical Decision Support**: Providing data-driven insights for diagnosis
- **Resource Allocation**: Prioritizing patients for further testing
- **Preventive Care**: Enabling proactive health management

## 🚀 How to Use

### For Google Colab Users:
1. Upload the `heart.csv` file to your Google Colab environment
2. Open the `Logistic_Regression_31_Jan_2025.ipynb` notebook in Colab
3. Run all cells sequentially to reproduce the analysis
4. The model will train and display performance metrics automatically

### File Structure
Heart-Disease-Prediction/
├── Logistic_Regression_31_Jan_2025.ipynb # Main Colab notebook
├── heart.csv # Dataset file
└── README.md # Project documentation

## 📊 Results Interpretation
- **High Recall Advantage**: The model's 89% recall means it rarely misses actual heart disease cases, making it suitable for medical screening where false negatives are critical
- **Feature Importance**: Medical professionals can focus on the most predictive clinical parameters identified by the model
- **Clinical Relevance**: The model complements traditional diagnostic methods with data-driven insights

## 🔮 Future Enhancements
- Integration with electronic health record systems
- Real-time prediction capabilities
- Expanded feature set including lifestyle factors
- Comparison with other machine learning algorithms

## 👨‍💻 Author
Lakshmi Bhavani Reddy
lakshmibhavani071200@gmail.com | https://www.linkedin.com/in/lakshmibhavanireddy37/  
Data Science Enthusiast passionate about healthcare applications of machine learning.

---

*This project demonstrates the practical application of machine learning in healthcare, showcasing end-to-end data science workflow from data preprocessing to model deployment-ready implementation.*
