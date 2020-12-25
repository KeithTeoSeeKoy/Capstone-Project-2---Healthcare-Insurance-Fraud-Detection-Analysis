# Capstone Project 2 - Healthcare Insurance Fraud Detection Analysis
This is an individual project done over 9 days. I've downloaded the Healthcare Insurance Fraud Detection dataset from Kaggle. This time round I did a Entity-Relation Diagram (ERD) in Dbeaver. Afterwhich, I've imported the data into the individual SQL table from the dataset I've downloaded. With these tables now populated with the data, I've used SQL to stitch up the tables (using SQL Join statement) I required so that I can output the files into Excel to facilitate my data analysis. After getting the two files I wanted, namely the Inpatient and Outpatient files, I used Power Query to do some minor clean up and transformation. Of course, I could have done these in the SQL environment if I want to. But in real life, when an analyst received unclean dataset, he would still need to know how to handle them.

Both the dashboard layout in Inpatient and Outpatient Analysis are similar. The analysis highlighted the top state where fraud claims is the highest, the healthcare provider and physician that are committing the most fraudulent claims. Of the charts, the most important lies in the Activity Table and Charts in each of the Dashboard. I've clearly pinpointed why each of these insurance claims are fraudulent in the Activity Table.

I've also included three Machine Learning Models (namely Logistic Regression, Decision Tree and Random Forest) to wrap up the prediction portion of this analysis work. Unlike, in my Capstone 1, I'm not using Excel Solver here. I'm using Python with xlwings acting as the bridge so that I'm able to read and write to Excel. Do note that I did not do any optimization in my three models. I'm using default models feeding the same dataset and test size for all three models.  

---
##### <<The file size related to this analysis is rather huge. Hence, I would not be able to make the analysis files available. However, should you be interested, you are still welcome to approach me.>>

---
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/FraudDetnWorkflow.JPG?raw=true" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/FraudDetnIp.JPG?raw=true" width="600"/>
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/FraudDetnOp.JPG?raw=true" width="600"/> 
<img src="https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/images/FraudDetnModel.JPG?raw=true" width="600"/>
