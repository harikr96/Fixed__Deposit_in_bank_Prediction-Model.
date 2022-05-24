# Fixed__Deposit_in_bank_Prediction-Model.
Based on the client's age, job type, marital status, etc., predicted if the client will make a fixed deposit with the bank using the Decision tree classification model. Which gave an accuracy score of 91%.


# Problem Statement
Client is a retail banking institution. Term deposits are a major source
of income for a bank.
A term deposit is a cash investment held at a financial institution. Your
money is invested for an agreed rate of interest over a fixed amount of
time, or term.
The bank has various outreach plans to sell term deposits to their
customers such as email marketing, advertisements, telephonic marketing
and digital marketing.
Telephonic marketing campaigns still remain one of the most effective way
to reach out to people. However, they require huge investment as large call
centers are hired to actually execute these campaigns. Hence, it is crucial
to identify the customers most likely to convert beforehand so that they can
be specifically targeted via call.

You are provided with the client data such as : age of the client, their job
type, their marital status, etc. Along with the client data, you are also
provided with the information of the call such as the duration of the call, day
and month of the call, etc. Given this information, your task is to predict if
the client will subscribe to term deposit

default =Credit in default.

housing =Housing loan

loan =Personal loan

contact= Type of communication

month =Contact month

day_of_week= Day of week of contact

duration =Contact duration

campaign =number of contacts performed during this
campaign to the client

pdays =number of days that passed by after the client
was last contacted

previous= number of contacts performed before this
campaign

poutcome =outcome of the previous marketing campaign

Subscribed= (target) has the client subscribed a term deposit?

### Tools and libraries used: 

Jupyter notebook, Python(NumPy, Pandas,
Scikit-learn, Matplotlib, Seaborn, SciPy)

## Machine learning algorithm used :

Logistic regression ; Accuracy score of 88%

Decision tree model: Accuracy score of 91%
  
  # Inference from the dataset given:
  
 1. From the data we can see the most of the customer have an age of 32

2. From the data we can see the most of the customer are married.

3. From the data we can see the most of the customer are having an secondary education.

4. From the data we can see the most of the customer have no credit in default.

5. Since it is a continous variable and the balance of different client will be different thats why we dont see any repeatation of balance in this particular data.

6. Most of the customer have housing loan.

7. Most of the client do not have personal loan.

8. Most of the client are using cellular mobiles for communication.
Majority of the client are called on 20th of respective month mostly they are contacted on may month .

9. The representatives have contacted the clients for an average for 90 hours and they have contacted most of the customer only ones.
 
10.  Also we can deduce more clients are contacted by representatives were fresh clients for the fixed term.




    From the above data's one can make certain changes for the approaches;

11. .Clients who are in the age of 30-40 should be contacted frequently and should be given more importance.

12 .Most of the clients are having blue collar jobs so, it is hard to predict the promising customer but analysing the transaction history , debt they hold,dependants of them will definitely helps to reach a conclusion.

13 .Married people should be approached with care by educating them with the importance of having a term deposit.

14 .Majority of the customer dont have credits in default which means they are promising customers.

15 .Clients who are having housing loan should be educated how the fixed term deposit is going to help them financially.

16 .Clients are approached at the middle of the month that is mostly on 20th day which should be changed to the first or second week which makes them comfortable with their money management.

17 .Campaign is done only one time towards the customer which can be done more without annoying the clients.


18. Blue collor,management,technician,administrative constitutes the majority of the job category


19. Clients in the age 0f 40-60 have higher balance ranging upto 100000


  20. contact duration for clients from 60-90 are less
  
  21. As a part of campaign clients having the age from 25-60 are contacted continously, with the      highest number of contact performed >60
  
  
  22. client id 28050 who has good profile should be approached more often.Campaigning has done only one time.


23. clients who have no history of default in credit have chance for subscription

24. Customer having personal loan is less likely to subscribe.
