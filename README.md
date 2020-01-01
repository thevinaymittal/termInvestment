# Term Investment 

An investor is any person or other entity (such as a firm or mutual fund) who commits capital with the expectation of receiving financial returns. Investors utilize investments in order to grow their money and/or provide an income during retirement,

A term investment is a fixed-term investment that includes the deposit of money into an account at a financial institution. Term deposit investments usually carry short-term maturities ranging from one month to a few years and will have varying levels of required minimum deposits.

# How this repository helpful
Assume a retail bank wants to study the success of telemarketing calls for selling the bank's long-term
deposits. We solved it by using some data mining (and machine learning) tools for this
purpose. Dataset collected is a large dataset comprising of 11,755 instances with 16 +
output = 17 attributes. 

The classification goal is to predict if the client will subscribe a term deposit (variable no. 17:y) based on the remaining 16 attributes.

# Dataset 
The dataset has been nicely split into train/dev/test partitions and is available to you. 

The description of the 17 attributes of dataset are as follows:

Input variables consisting of background data from the bank’s 11,755 clients:
1 - age
2 - job : type of job
3 -marital:maritalstatus
4 -education
5 - default: has credit in default?
6 -balance:averageyearlybalance,ineuros
7 - housing: has housing loan?
8 - loan: has personal loan?

The following attributes are related with the last contact of the current telemarketing campaign:
9 - contact: contact communication type
10-day:lastcontactdayofthemonth
11-month:lastcontactmonthofyear
12 -duration:lastcontactduration,inseconds


Other recorded attributes are:

13 - campaign: number of contacts performed during this campaign and forthis client
14-pdays:numberofdaysthatpassedbyaftertheclientwaslastcontactedfroma
previous campaign (-1 means client was not previously contacted)
15 - previous: number of contacts performed before this campaign and forthis client
16 - poutcome: outcome ofthe previous marketing campaign
Output variable (desired target):
17 - y - has the client subscribed a term deposit?

# What is in the code

The Decision Trees and k-Nearest Neighbours algorithms are used in order to train models to  perform a binary classification task on a dataset about a bank’s long-term deposits.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
Open Source
