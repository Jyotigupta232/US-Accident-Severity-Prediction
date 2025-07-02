# US Accident Severity Prediction 🚦

**SkillCraft Internship – Task 4**

This project explores the prediction of traffic accident severity across the United States using weather and time-related factors. Using a Decision Tree Classifier, we developed an interpretable model that helps understand which features most impact accident severity — enabling both prediction and insight.

📊 Dataset
- **Source**: [US Accidents Dataset - Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Records**: 4.2 million+
- **Features used**:
  - Temperature (F)
  - Humidity (%)
  - Wind Speed (mph)
  - Visibility (mi)
  - Hour of Day (derived from Start Time)

🛠️ Tools & Libraries
- Python
- Jupyter Notebook
- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `scikit-learn` (DecisionTreeClassifier, model metrics, visualization)

🔍 Project Objectives
- Understand how environmental and temporal factors affect accident severity
- Build an **interpretable machine learning model**
- Evaluate model performance using common classification metrics
- Visualize the decision tree for better understanding of decision boundaries

## Key Steps
1. Data Cleaning & Preprocessing
2. Feature Engineering (extracted 'Hour' from timestamp)
3. Model Training using Decision Tree Classifier
4. Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
5. Visualization of the Tree Structure using `sklearn.tree.plot_tree`

## Results & Observations
- Accidents occurring in **low visibility**, **high humidity**, or **certain hours of the day** tend to have higher severity.
- The Decision Tree model provides **explainable predictions**, ideal for risk profiling and decision support.


