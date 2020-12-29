# Final Assignment
In this Assignment, you will demonstrate your understanding of the data science methodology by applying it to a given problem. Pick one of the following topics to apply the data science methodology to:
1. Emails
2. Hospitals
3. Credit Cards
You will have to play the role of the client as well as the data scientist to come up with a problem that is more specific but related to these topics. Please note that this assignment is worth 10% of your final grade.
----
### Question 1: Which topic did you choose to apply the data science methodology to? (2 marks)
**Answer:** I have chosen the topic of **Hospitals**.

### Question 2: Using the topic that you selected, complete the Business Understanding stage by coming up with a problem that you would like to solve and phrasing it in the form of a question that you will use data to answer. (3 marks)
### You are required to:
### Describe the problem, related to the topic you selected.
### Phrase the problem as a question to be answered using data.

**Answer:** In 2020, COVID-19 pendemic has devistated the world. From north to south and from east to west, no counrty is safe from the devistated effects of the virus. The efefcts and impact of the virus are not fully understand. The virus is mutating as well. I want to use the power of data science to understand the virus better and to predict the outbreak of the new strain of crona virus. My question is:

"Can we identify the new virus mutation and the location by analysing the Hospital records?"

### Question 3: Briefly explain how you would complete each of the following stages for the problem that you described in the Business Understanding stage, so that you are ultimately able to answer the question that you came up with. (5 marks):

**Answer:**

**Analytic Approach**

We will use a **decision tree classsification model** to answer the Yes/NO question about the condition of the patients.

**Data Requirements**

To build our model, we use patient hospital data of COVID patients, their demographic data as well as the data from all the testing labs. Also, a patient travel history data is required for location prediction. As the vaccines are also rolling out, this data will also be benificial.

**Data Collection**

Hospital records of the COVID patients, their demographic data can be collected from hospitals. Testing Labs data and airlines passanger data will be collected. Also, the data related to vaccines are not available at the moment but can be included in the future.

**Data Understanding and Preparation**

In this step we need to evaluate the different variables of our data in order to undestant it better. The descriptive statistics and visualization techniques can be used to better understand the data and get acquainted with it. We can use univariate statistics and the correlation between different variables. We also need to evaluate the quality of the data. Strategies must be deviced to takle missing and invalid data. This step will help us to identify the missing data and whether we need more data sources.

**Modeling and Evaluation**

We will use differnt machine learning techniques like regression analysis to fit our model and use predictive modeling techniques to train the data set. For evaluation stage, we will use the test data to evaluate the out of the model prepared. Diagnostic measures can be use to evaluate the model. If required, the model can be refined to give better results.
 
