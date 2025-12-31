**Project Title** - 
Lead Scoring Model using Logistic Regression

**Overview** - 
This project focuses on building a lead scoring model for an education company to improve its lead conversion rate. Using historical lead data, a logistic regression model is developed to assign a score to each lead that represents the likelihood of conversion. This enables the sales team to focus on high-potential leads and improve overall efficiency.

**Business Problem** - 
X Education generates a large number of leads through online marketing channels, but only about 30 percent of these leads convert into paying customers. The sales team currently spends time contacting all leads, resulting in low efficiency. The company wants to identify high-quality leads, referred to as hot leads, to increase the conversion rate to around 80 percent.

**Objective** - 
Build a logistic regression model that assigns a lead score between 0 and 100 to each lead, where higher scores indicate higher chances of conversion. Provide business recommendations based on the model to help the company improve its lead nurturing and conversion strategy.

**Data Description** - 
The dataset contains around 9000 leads with attributes such as lead source, website engagement metrics, and last activity.
The target variable is Converted, where 1 indicates a successful conversion and 0 indicates no conversion.
Categorical values labeled as Select are treated as missing values and handled appropriately.

**Approach** - 
Performed data cleaning and exploratory data analysis
Handled missing values and replaced invalid categorical levels
Encoded categorical variables and scaled numerical features
Built a logistic regression model to predict lead conversion
Evaluated model performance using accuracy, precision, recall, and ROC AUC
Generated lead scores from predicted probabilities
Addressed future business scenarios using model insights

**Key Insights** - 
Website engagement variables strongly influence conversion probability
Certain lead sources show significantly higher conversion rates
Focused targeting of high-score leads can substantially improve conversion efficiency
The model provides flexibility to adjust strategies based on changing business requirements

**Model Evaluation** - 
Model performance evaluated using classification metrics and probability-based scoring to support business decision-making.

**Tools and Technologies** - 
Python
Pandas and NumPy
Matplotlib and Seaborn
Scikit learn
Statsmodels
Jupyter Notebook

**Deliverables** - 
Commented Python notebook with model building, predictions, and evaluation
Word document with answers to business questions
Presentation in PDF format summarizing technical and business insights
Summary report submitted as a PDF

**Author** - 
Hritik Vijay Thorat
Data Analyst with interest in Predictive Modeling and Business Analytics
