**Feature Engineering & Selection**

This document is a precursor to the Feature Engineering & Selection report. The project was based on the Heritage Health Prize hosted by Kaggle, sponsored by HPN. 
The purpose of this project is to predict the number of days spent in the hospital based on several features, such as Charlson Index, number of drug prescriptions, medical history, lab work, among several others. 

**Primary Steps**

1. Feature Engineering
2. Feature Selection
3. Linear Regression

The majority of the work was in the Feature Engineering and Selection stages, where data was cleaned, and transformed to make it model ready. In these two sections, certain decisions were made which were tradeoffs against other decisions. These decisions were made in the midst of solving the problem, and were often considered best practices at the time it was executed. The selected features from the tidy dataset was put through a linear regression model to predict the features affecting the number of days spent in the hospital the next year. 

Another philosophy that was held over the course of this problem was simplification. In the pursuit of simplifying the regression model, I eliminated features that were deemed unnecessary and only used claims data pertaining to one year. This helped reduce model complexity and allowed me to focus on learning the process of feature engineering and selection. I’ll be able to build on the skills I’ve learned from this project and apply them to more complex problems.

**Takeaway**

This was the first project where I was tasked with cleaning multiple sets of data and combining them before analyses. There were a few key takeaways:

1. Questioning assumptions and re-evaluating previous decisions with regards to data cleaning. 
2. Transforming datasets to show a unique ID for each row (think: creating a wide dataset). 
3. Building a model appropriate to the context of the problem. Complex != better. 
