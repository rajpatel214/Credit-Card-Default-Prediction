# Project 5  Loan Status 

**Steps of the Project**

**1. Understanding the Data**
We first explored the dataset to check the number of records, types of data (numerical or text), and any missing values. Basic statistics like average, minimum, and maximum values helped us understand the dataset better.

**2. Handling Missing Data**
Some columns had missing values, which could impact the analysis. Instead of removing these rows, we replaced missing values with similar existing values from the same column to maintain data consistency.

**3. Analyzing and Visualizing the Data**
To understand financial trends, we used different visualizations:
Boxplot to check the distribution of credit limits and detect any unusual values.
Histogram to analyze the age distribution of credit card holders.
Bar charts to compare total bill amounts and payment amounts across different months.
Pie chart to show the percentage of people who defaulted versus those who paid on time.

**4. Identifying Key Financial Patterns**
We calculated and analyzed the average, minimum, and maximum payments made by customers. This helped us understand their payment behavior and detect any inconsistencies.

**5. Training Machine Learning Models**
To predict credit card defaults, we used different machine learning models. First, we converted text-based data into numerical form so that the model could process it. Then, we split the dataset into training data (80%) to teach the model and testing data (20%) to evaluate its accuracy.

**6. Evaluating Model Performance**
We tested multiple models and compared their accuracy:
**Naïve Bayes:** 77%
**Decision Tree:** 79% (Best performing)
**Random Forest:** 78.3%
**Support Vector Machine (SVC):** 73.8%

**Final Conclusion**
The project helped identify key factors contributing to credit card defaults.
Customers with higher unpaid bills and irregular payment history were more likely to default.
The Decision Tree model performed best, achieving 79% accuracy, making it a useful tool for predicting credit risks.
