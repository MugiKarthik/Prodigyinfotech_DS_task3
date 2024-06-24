# Prodigyinfotech_DS_task3
Data science internship from Prodigy InfoTech

![image](https://github.com/MugiKarthik/Prodigyinfotech_DS_task3/assets/159174033/d8dd14e5-617b-4258-aed8-da12293a28ae)

# Task 3
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

# About the data:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

Variable Name	Role	Type	Demographic	Description	Units	Missing Values
age	Feature	Integer	Age			no
job	Feature	Categorical	Occupation	type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')		no
marital	Feature	Categorical	Marital Status	marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)		no
education	Feature	Categorical	Education Level	(categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')		no
default	Feature	Binary		has credit in default?		no
balance	Feature	Integer		average yearly balance	euros	no
housing	Feature	Binary		has housing loan?		no
loan	Feature	Binary		has personal loan?		no
contact	Feature	Categorical		contact communication type (categorical: 'cellular','telephone')		yes
day_of_week	Feature	Date		last contact day of the week		no
month	Feature	Date		last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')		no
duration	Feature	Integer		last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.		no
campaign	Feature	Integer		number of contacts performed during this campaign and for this client (numeric, includes last contact)		no
pdays	Feature	Integer		number of days that passed by after the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted)		yes
previous	Feature	Integer		number of contacts performed before this campaign and for this client		no
poutcome	Feature	Categorical		outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')		yes
y	Target	Binary		has the client subscribed a term deposit?		

link - https://archive.ics.uci.edu/dataset/222/bank+marketing

# Conclusion:
Building a decision tree classifier to predict customer purchases based on demographic and behavioral data, using the Bank Marketing dataset from the UCI Machine Learning Repository, successfully demonstrated the power of machine learning in customer behavior prediction. By preprocessing the data, encoding categorical variables, and splitting the dataset into training and testing sets, the decision tree model was trained and evaluated for accuracy. The resulting classifier effectively identified key features influencing purchase decisions, providing valuable insights into customer behavior patterns and enhancing the ability to target potential buyers with greater precision.

# Contact Information:
Feel free to give me any suggestions or feedback: 
[linkedin karthik m](https://www.linkedin.com/in/karthik-m-97b759202/)
Email - mugikarthikofficial@gmail.com
