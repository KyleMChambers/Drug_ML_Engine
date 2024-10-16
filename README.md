# Drug Effectiveness and Satisfaction Analysis

## Project Overview
Overall, this project demonstrated the application of machine learning techniques to real-world healthcare data but also highlighted the critical role that user satisfaction plays in the success of pharmaceutical products. This project analyzed the relationship between drug effectiveness, ease of use, and user satisfaction. I built a predictive model to using linear regression to estimate user satisfaction based on key features: effectiveness and ease of use, and user satisfaction.

### Model Performance
The model achieved a R-squared value of approximately 71.9%, indicating that it effectively captures a significant portion of the variability in user satisfaction scores. This suggests that the chosen predictors—effectiveness and ease of use—are strong indicators of user satisfaction with the drugs analyzed.

### Actionable Insights
The findings could inform healthcare/pharma companies and healthcare providers about the importance of drug effectiveness and user experience in driving patient satisfaction. This knowledge can guide future product development, marketing strategies, and customer engagement efforts.

## Objectives

- Understand the relationships between drug effectiveness, ease of use, and user satisfaction.
- Build a predictive model using machine learning to estimate user satisfaction based on relevant features.

## Data Preparation

1. **Data Importing:** 
   - Loaded the dataset containing features like condition, drug name, effectiveness, ease of use, and user satisfaction scores.

2. **Data Cleaning:** 
   - Processed the data to remove irrelevant or problematic information.

## Exploratory Data Analysis (EDA)

- **Statistical Summary:** 
  - Analyzed basic statistics of numerical columns to understand the dataset better.

- **Distribution Analysis:** 
  - Plotted histograms to visualize the distributions of effectiveness, ease of use, and satisfaction scores.

- **Correlation Analysis:** 
  - Created a heatmap to understand how these variables correlate, particularly focusing on the relationship between effectiveness, ease of use, and satisfaction.

## Model Building

1. **Data Splitting:** 
   - Divided the dataset into training and testing sets to evaluate the model's performance.

2. **Model Selection:** 
   - Selected a linear regression model to predict satisfaction based on the independent variables (effectiveness and ease of use).

3. **Model Training:** 
   - Trained the model using the training dataset.

## Model Evaluation

- **Performance Metrics:** 
  - Calculated the Mean Squared Error (MSE) and R-squared value to assess the model's accuracy. The R-squared value indicated that approximately 71.9% of the variability in satisfaction could be explained by the model.

- **Visualization:** 
  - Created a scatter plot comparing actual vs. predicted satisfaction scores to visually assess model performance.

## Insights and Future Steps

- Gained insights into how effectively the model captured relationships between the input features and the target variable (satisfaction).
- Discussed ways to iterate on the model, such as trying different algorithms, tuning hyperparameters, or including more features.

## Takeaways

- **Understanding Relationships:** 
  - This project helped us understand the relationships between drug effectiveness, ease of use, and user satisfaction.

- **Predictive Modeling Skills:** 
  - Developed skills in data preprocessing, exploratory data analysis, model building, and evaluation using Python libraries like Pandas, Scikit-Learn, and Seaborn.

- **Actionable Insights:** 
  - Findings from the model could inform decision-making in a real-world context, helping stakeholders understand which factors are most influential in driving user satisfaction with drugs.

## Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name
