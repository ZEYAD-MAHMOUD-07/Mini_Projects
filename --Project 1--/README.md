📊 Telecom Customer Churn Analysis (Mini Project)
🎯 Objective
The main goal is to identify relationships between customer churn and other features such as tenure, contract type, monthly charges, and service type.
📁 Dataset
Dataset: Telecom Customer Churn
Rows: 7,043
Description: Customer demographic, service, and billing information
🛠️ Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
🧪 Project Steps
Data Understanding & Exploration
Reading the dataset
Understanding columns and data types
Data Cleaning
Removed 3 rows containing critical null values
Kept some rows with minor missing values (e.g. tenure-related)
Visualization & Analysis
Used multiple visualizations to explore relationships
Extracted insights based on both visuals and numeric analysis
📌 Key Insights
❌ No clear relationship between Churn and Monthly Charges
❌ No clear relationship between Churn and Internet Service Type (Fiber / DSL / No Internet)
✅ Strong relationship between Churn and Tenure
63.63% of churned customers stayed less than 18 months
✅ Strong relationship between Churn and Contract Type
Month-to-month contracts have the highest churn rate
One-year and two-year contracts are much more stable
✅ Conclusion
Customer churn is strongly influenced by how long the customer stays and the type of contract, while pricing and service type showed no significant impact in this analysis.
This project demonstrates a complete EDA workflow: understanding data, cleaning it, visualizing patterns, and extracting meaningful insights.
