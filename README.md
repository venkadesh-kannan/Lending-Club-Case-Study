# Lending Club Case Study - UPGRAD



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- I assume to work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
-   If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
-   If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

  The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
  In this case study, I will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
    
    When a person applies for a loan, there are two types of decisions that could be taken by the company:
      Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
        Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
        Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
        Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

      Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 

Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

To develop our understanding of the domain, I am advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

Data Set:
It contains the complete loan data for all loans issued through the time period 2007 t0 2011. data dictionary which describes the meaning of these variables is also attached.


## Conclusions
Conclusions
Loan amount, investor amount, funding amount are strongly correlated.
Annual income with DTI(Debt-to-income ratio) is negatively correlated.
Customers who are getting &#39;charged off&#39; have lower annual incomes than the ones who paid fully for every grade (i.e. at same interest range), hence Lending club should put threshold on the maximum loan amount to be disbursed to such applicants, if at all. And along with it. it is recommended that Lending Club shorten the repayment tenure as well.
Grades are good metric for detecting defaulters. Lending Club should examine more information from borrowers before issuing loans to Low grade (G to A)
Lending Club should control the number of loans issued to borrowers who are from CA, FL and NY to make profits
Borrowers with mortgage home ownership are taking higher loans and defaulting on the approved loans. Lending club can put a threshold for such customers or add additional clauses before approving such loans
Lending club should also reduce the tenure of repayment months to slash the percentage of ‘Charged Off’ applications.
The lending club should make sure there are no public derogatory records for borrowers as these types of people have more chance of filing a bankruptcy.
Since Loan taken for Small Business purpose, Debt consolidation and Credit cards, are somewhat evenly distributed as compared to loan taken for other purposes, lending club can focus on these segments.
The lending club should stop giving loans to the above category when the loan amount requested is more than 12000 Changes to be done in Acknowledgements section
  
Changes to be done in Contact


## Technologies Used
python == 3.10.5
numpy==2.0.2
pandas==2.2.2
seaborn==0.13.2
re==2.2.1
platform==1.0.8


## Acknowledgements
  This project was inspired by Upgrad and was completed inn collaboration with Saumya Singh, Email: its.saumyah@gmail.com.

## Contact
Created by [@porshebeau]in collaboration with [@Venkadesh-kannan] . Feel free to contact us!

