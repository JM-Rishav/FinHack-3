# FinHack-3
LTFS Data Science FinHack 3 - (1FHMA) 

<br> In this finhack, you will develop a model for the business challenge "Upsell Prediction"</br>
<h2> LTFS Top-up loan Up-sell prediction </h2>
A loan is when you receive the money from a financial institution in exchange for future repayment of the principle, plus interest. Financial institutions provide loans to the industries, corporates and individuals. The interest received on these loans is one among the main sources of income for the financial institutions.
A top-up loan, true to its name, is a facility of availing further funds on an existing loan. When you have a loan that has already been disbursed and under repayment and if you need more funds then, you can simply avail additional funding on the same loan thereby minimizing time, effort and cost related to applying again.
LTFS provides it's loan services to its customers and is interested in selling more of its top-up loan services to its existing customers so they have decided to identify when to pitch a top-up during the original loan tenure.
If they correctly identify the most suitable time to offer a top-up, this will ultimately lead to more disbursals and can also help them beat competing offerings from other institutions.
<img src="https://github.com/JM-Rishav/FinHack-3/blob/main/Final%20data/PS_1.png">

<br> </br>
To understand this behaviour, LTFS has provided data for its customers containing the information whether that particular customer took the Top-up service and when he took such Top-up service, represented by the target variable Top-up Month.

You are provided with two types of information: 

1. Customer’s Demographics: The demography table along with the target variable & demographic information contains variables related to Frequency of the loan, Tenure of the loan, Disbursal Amount for a loan & LTV.
2. Bureau data:  Bureau data contains the behavioural and transactional attributes of the customers like current balance, Loan Amount, Overdue etc. for various tradelines of a given customer
As a data scientist, LTFS  has tasked you with building a model given the Top-up loan bucket of 128655 customers along with demographic and bureau data, predict the right bucket/period for 14745 customers in the test data.


<h3> Data Dictionary </h3>

<br>Train_Data.zip</br> 
This zip file contains the train files for demography data and bureau data. The data dictionary is also included here.

<br>Test_Data.zip</br>
This zip file contains information on demography data and bureau data for a different set of customers

<br>Sample Submission</br>
This file contains the exact submission format for the predictions. Please submit CSV file only.

<br>Variable	Definition</br>
ID	Unique Identifier for a row
<br>Top-up Month	(Target) bucket/period for the Top-up Loan</br>



## Feel free to give suggestions regarding project or any issues !!





