# Forage-BCG
Hello Readers!
This project is a virtual internship offered by BCG to provide a real time work experience.
This project use data to advise your client, PowerCo, on how to retain their customers with the team at BCG X
Below is the certificate of completion.
<img width="1123" alt="Screenshot 2024-02-08 at 11 50 44" src="https://github.com/kast424/Projects-2024/assets/146436395/3116e224-5078-4b74-8073-b893ab83bf2c">


The tasks are as below:
**Task 1:**
The brief from PowerCo:
The Associate Director (AD) of the Data Science team held a team meeting to discuss the client brief. You’ll be working closely with Estelle Altazin, a senior data scientist on your team.

Here are the key takeaways from the meeting:

Your client is PowerCo - a major gas and electricity utility that supplies to small and medium sized enterprises.
The energy market has had a lot of change in recent years and there are more options than ever for customers to choose from.
PowerCo are concerned about their customers leaving for better offers from other energy providers. When a customer leaves to use another service provider, this is called churn.
This is becoming a big issue for PowerCo and they have engaged BCG to help diagnose the reason why their customers are churning.

During the meeting your AD discussed some potential reasons for this churn, one being how “sensitive” the price is. In other words, how much is price a factor in a customer’s choice to stay with or leave PowerCo?

So, now it’s time for you to investigate this hypothesis. Your task - we need to understand PowerCo’s problem in detail
First things first, you and Estelle need to understand the problem that PowerCo is facing at a deeper level and plan how you’ll tackle it. If you recall the 5 steps in the Data Science methodology, this is called “business understanding & problem framing”.

Your AD wants you and Estelle to email him by COB today outlining:

the data that we’ll need from the client, and
the techniques we’ll use to investigate the issue.

**Task 2:**
Exploratory Data Analysis
Here is the background information on your task The BCG project team thinks that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data and the AD wants you to perform some exploratory data analysis.

The data that was sent over includes:

Historical customer data: Customer data such as usage, sign up date, forecasted usage etc Historical pricing data: variable and fixed pricing data etc Churn indicator: whether each customer has churned or not

Please submit analysis in a code script, notebook, or PDF format.

Please note, there are multiple ways to approach the task and that the sample answer is just one way to do it.

##Sub-Task 1:

Perform some exploratory data analysis. Look into the data types, data statistics, specific parameters, and variable distributions. This first subtask is for you to gain a holistic understanding of the dataset. You should spend around 1 hour on this. ##Sub-Task 2:

Verify the hypothesis of price sensitivity being to some extent correlated with churn. It is up to you to define price sensitivity and calculate it. You should spend around 30 minutes on this. ##Sub-Task 3:

Prepare a half-page summary or slide of key findings and add some suggestions for data augmentation – which other sources of data should the client provide you with and which open source datasets might be useful? You should spend 10-15 minutes on this.

For your final deliverable, please submit your analysis (in the form of a jupyter notebook, code script or PDF) as well as your half-page summary document.

Note: Use the 2 datasets within the additional resources for this task and if you’re unsure on where to start with visualizing data, use the accompanying links. Be sure to also use the data description document to understand what the columns represent. The task description document outlines the higher-level motivation of the project. Finally, use the eda_starter.ipynb file to get started with some helper functions and methods.
**Task 3:**
Feature Engineering & Modelling
##Sub-Task 1

Your colleague has done some work on engineering the features within the cleaned dataset and has calculated a feature which seems to have predictive power.

This feature is “the difference between off-peak prices in December and January the preceding year”.

Run the cells in the notebook provided (named feature_engineering.ipynb) to re-create this feature. then try to think of ways to improve the feature’s predictive power and elaborate why you made those choices.

##Sub-Task 2

Now that you have a dataset of cleaned and engineered features, it is time to build a predictive model to see how well these features are able to predict a customer churning. It is your task to train a Random Forest classifier and to evaluate the results in an appropriate manner. We would also like you to document the advantages and disadvantages of using a Random Forest for this use case. It is up to you how to fulfill this task, but you may want to use the below points to guide your work:

Ensure you’re able to explain the performance of your model, where did the model underperform? Why did you choose the evaluation metrics that you used? Please elaborate on your choices. Document the advantages and disadvantages of using the Random Forest for this use case. Do you think that the model performance is satisfactory? Give justification for your answer. (Bonus) - Relate the model performance to the client's financial performance with the introduction of the discount proposition. How much money could a client save with the use of the model? What assumptions did you make to come to this conclusion? You should spend 1 - 1.5 hours on this. When it comes to model evaluation and the explanation of your results, feel free to use the additional links below.

##If you are stuck:

##Sub-Task 1

Think of ways to evaluate a feature against a label. Think of ways to add new features which would complement the already existing ones. Think of feature granularity. Remove unnecessary features. ##Sub-Task 2

Is this problem best represented as classification or regression? What kind of model performance do you think is appropriate? Most importantly how would you measure such a performance? How would you tie business metrics such as profits or savings to the model performance?

**Task-4:**
Outline for making your predictions
It is your task to:

Train a random forest classifier to predict churn
Evaluate the predictions using evaluation metrics to demonstrate how accurately the model has performed
