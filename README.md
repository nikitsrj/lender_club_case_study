# Lending Club Case Study - IIIT-B Assignment (Exploratory Data Analysis)
> Risk Analysis for a Consumer Finance company where we want to help company to take decisions to offer loan to a particular applicant or not. Risks are identified based on the applicant's profile..


## Table of Contents
* [Situation](##Situation)
* [Task](##Task)
* [Action](##Action)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Situation
We work for a consumer finance company that specializes in lending various types of loans to urban customers. When we receive a loan application, we have to make a decision for loan approval based on the applicant's profile.There are two types of risks are associated with our decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business for us.
* If the applicant is not likely to repay the loan, i.e., they are likely to default, then approving the loan may lead to a financial loss for our company.

The following provided data contains information about past loan applicants and whether they 'defaulted' or not. Our aim will be to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc. At this moment the company have the data of individual whose Loan had been accepted and falls under three categories.

1. Who had paid full loan along with interest
2. Who is still in the process of paying the installments and had been paying at time
3. Who haven't paid the installments in due time for long period of time.

## Task
This company is like a big online store for loans which help people get personal loans, business loans, and even pay for medical procedures. The company had made it really easy for people to apply for a loan online and get a good interest rate.

But, just like any other loan company, It sometimes lose money when people don't pay back the money they borrowed. This is called "credit loss." Basically, when borrowers don't pay their loans or disappear without repaying, it causes a lot of financial trouble for the company. In this case, the customers who don't pay their loans are called "charged-off."

So, now our task is to help the company to figure out who these risky borrowers are before giving them a loan. If we can do that, they can reduce the amount of money they lose from people not paying back their loans. We will be using a method called "Exploratory Data Analysis" (EDA) to find out which factors or information about the borrowers are strong signals that someone might not pay back their loan.

In simple terms, The company want to understand what things make it more likely for someone to not repay their loan. This way, they can be smarter about who they give loans to and reduce their financial risk.

## Action
Our approach to help the company to understand or analyse more about the financial risk will be done by following steps on Data provided to us.

1. Data Cleaning: We will be Removing the null valued columns, unnecessary variables and checking the null value percentage and removing the respective rows.
2. Data Understanding: We will be working with the data dictionary and getting knowledge of all the columns and their domain specific uses
3. Univariate Analysis: We will be analysing each column and plotting the distributions of each column.
4. Segmented Univariate Analysis: We will be Analysing the continuous data columns with respect to the categorical column
5. Bivariate Analysis: We will be analysing the two variable behaviour like term and loan status with respect to loan amount.
6. Insights: We will analyse all plots and recommendations for reducing the loss of business by detecting columns best which contribute to loan defaulters.

## Conclusions
Recommendations

-Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
1. DTI
2. Grades
3. Verification Status
4. Annual income
5. Pub_rec_bankruptcies
- Other considerations for 'defaults' :
1. Borrowers not from large urban cities like california, new york, texas, florida etc.
2. Borrowers having annual income in the range 50000-100000.
3. Borrowers having Public Recorded Bankruptcy.
4. Borrowers with least grades like E,F,G which indicates high risk.
5. Borrowers with very high Debt to Income value.
6. Borrowers with working experience 10+ years.

## Technologies Used
- Panda
- NumPy
- Seaborn
- Matplotlib
- Plotly

## Acknowledgements
- This project was inspired by UpGrad IIITB Program as a case study for AI/ML Course

## Contact
Created by [@nikitsrj] - feel free to contact me!
