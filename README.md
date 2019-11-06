# Approving-Customers-Loan-Request-Predictor


### Problem statement :
If any customer has applied for a loan of 1,000,000 Rs, the bank and investors needs to perform a due diligence on the requested loan application. To develop an Machine Learning model to check whether the applicant's loan should be approved (capable to pay loan back) or not.



### Alogrithms (Hpypertuned):
     -  Logistic Regression
     -  K-Nearest Neighbors Classifier
     -  Decision Tree Classifier
     -  Support Vector Classifier
     -  Random Forest Classifier
     -  Bagging (On Decision Tree)
     -  Xtra Tree Classifier
     -  Stochastic Gradient Descent
     -  Gradient Boosting Machine
     -  Adaboost Classifier
     -  XGBoost Classifier
     
     
     
     
 ### Results (Accuracy and F1-score):
 
 ![results](https://user-images.githubusercontent.com/47252506/68310027-5908bb80-00d5-11ea-8a96-17073cc527f6.png)





### Information about the dataset ####

1. Number of Instances: 500000+ 

2. Number of Attributes: 40+

3. Contains missing Attribute Values

4. Attribute Information:

                  Attribute:                     Description:
        ------------------            -----------------------------------------------
        
        member_id                       unique ID assigned to each member
        loan_amnt                       loan amount ($) applied by the member
        funded_amnt                     loan amount ($) sanctioned by the bank
        funded_amnt_inv                 loan amount ($) sanctioned by the investors
        term                            loan (in months)
        batch_enrolled                  batch numbers allotted to members
        int_rate                        interest rate (%) on loan
        grade                           grade assigned by the bank
        sub_grade                       grade assigned by the bank1
        emp_title                       job / Employer title of member
        emp_length                      employment length, where 0 means less than one year and 10 means ten or more years
        home_ownership                  status of home ownership
        annual_inc                      annual income ($) reported by the member
        verification_status             status of income verified by the bank
        pymnt_plan                      indicates if any payment plan has started against loan
        desc                            loan description provided by member
        purpose                         purpose of loan
        title                           loan title provided by member
        zip_code                        first three digits of area zipcode of member
        addr_state                      living state of member
        dti                             ratio of member's total monthly debt repayment excluding mortgage
        delinq_2yrs                     number of 30+ days delinquency in past 2 years
        inq_last_6mths                  number of inquiries in last 6 months
        mths_since_last_delinq          number of months since last delinq
        mths_since_last_record          number of months since last public record
        open_acc                        number of open credit line in member's credit line
        pub_rec                         number of derogatory public records
        revol_bal                       total credit revolving balance
        revol_util                      amount of credit a member is using relative to revol_bal
        total_acc                       total number of credit lines available in members credit line
        initial_list_status             unique listing status of the loan - W(Waiting), F(Forwarded)
        total_rec_int                   interest received till date
        total_rec_late_fee              Late fee received till date	
        recoveries                      post charge o" gross recovery
        collection_recovery_fee         post charge o" collection fee 11
        collections_12_mths_ex_med      number of collections in last 12 months excluding medical collections
        mths_since_last_major_derog     months since most recent 90 day or worse rating
        application_type                indicates when the member is an individual or joint
        verification_status_joint       indicates if the joint members income was verified by the bank
        last_week_pay                   indicates how long (in weeks) a member has paid EMI after batch enrolled
        acc_now_delinq                  number of accounts on which the member is delinquent
        tot_coll_amt                    total collection amount ever owed
        tot_cur_bal                     total current balance of all accounts
        total_rev_hi_lim                total revolving credit limit
        loan_status                     status of loan amount, 1 = Defaulter, 0 = Non Defaulters
