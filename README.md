## Background
The dataset used in this personal project was collected from the donor database of a Blood Transfusion Service Center in Hsin-Chu City, Taiwan (specifically, a mobile blood donation vehicle). he center passes its blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months. 
**My task is to predict whether or not a donor will give blood the next time the vehicle comes to campus.**

## Procedure
- In this project, I try something different: I use TPOT, a python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming. What's interesting about TPOT is the fact that once it is finished searching, it provides you with the Python code for the best pipeline it found so you can tinker with the pipeline from there. 
- This means that for this project, I do not exactly start by doing the good old Exploratory Data Analysis. Nevertheless, I am pleased with the initial level of performance that my model exhibits and would most definitely have an easy time improving its performance. 
- The data is structured according to the RFMTC marketing model (a variation of RFM): Recency, Frequency and Monetary Value and it is commonly used in marketing for identifying a company's best customers. In this case, our customers are blood donors.
