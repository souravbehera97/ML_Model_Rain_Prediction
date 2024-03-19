# Rainfall Prediction in Sydney - Machine Learning Project

## Problem Statement
The goal of this project is to develop machine learning models capable of accurately predicting rainfall in Sydney based on historical weather data. The dataset covers weather-related variables from 2008 to 2017, and the objective is to leverage these data to build robust predictive models.

## Approach
1. **Data Preprocessing:**
   - Convert categorical variables into dummy variables.
   - Replace missing values with the mean.
   - Check for outliers in the rainfall data.
   
2. **Model Selection:**
   - Utilize a range of classification models, including Decision Trees, Random Forest, Gradient Boosting, AdaBoost, XGBoost, Logistic Regression, K-Nearest Neighbors, and Linear Discriminant Analysis.
   
3. **Model Training and Evaluation:**
   - Split the data into training and testing datasets.
   - Train each model on the training dataset.
   - Evaluate model performance using accuracy, ROC AUC, recall, and precision.
   
4. **Model Comparison:**
   - Compare the performance of different models to select the best-performing one.

5. **Model Optimization:**
   - Fine-tune model hyperparameters using GridSearchCV to improve accuracy.

## Models Implemented
- Decision Trees
- Random Forest
- Gradient Boosting
- AdaBoost
- XGBoost
- Logistic Regression
- K-Nearest Neighbors
- Linear Discriminant Analysis

## Output Files
- Performance metrics for each model on both training and testing datasets.
- Best hyperparameters for each model.
- Confusion matrices, accuracy, precision, recall, and ROC AUC scores for evaluation.

## Usage
1. Clone the repository: `[git clone https://github.com/your_username/your_repository.git`](https://github.com/souravbehera97/ML_Model_Rain_Prediction)
2. Navigate to the project directory: `cd your_repository`
3. Run the Jupyter Notebook or Python script to execute the code.
4. View the output files to analyze model performance and results.

## Contributors
- Sourav Kumar Behera- https://github.com/souravbehera97

## References
- Dataset source: Internshala

## Note
- This project is for educational and demonstrative purposes.
- For any inquiries or issues, please contact beherasourav259@gmail.com.
