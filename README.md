# world-bank-data-analysis

Data Analysis of World bank loan/credit data and report building in Tableau


## Background

World bank divided into 2 sections :  
IBRD - for developed nations with middle/high income nations    
IDA - for developing nations with free/less interest loans     
As it is a financial institution, performing credit checks and analysis is extremely crucial to make decisions about which countries and sectors to invest in.     


## Problem Statement 

● The scale on which World bank loans money to nations is massive. To avoid situations where such massive amounts end up being unpaid, it is extremely crucial to have rigourous credit checks and historical analysis before making investment decisions to avoid repayment frauds/ defaulters     

● Being mindful of how funds are allocated to nations based on their financial situation needs to be analyzed to avoid inadequate financial support to developing nations     

● Background checks and historical analysis is necessary to make decisions of Region/ Sector wise loan approval based on previous repayment patterns       


## Project Goal

● To analyze the financial capacity of the borrower as massive amount of finances are involved and credit check is extremely necessary to avoid repayment frauds/ defaults    

● To analyze the funds granted for the upliftment of developing nations by providing financial help (IBDR and IDA distinction)     

● To analyze the timeframe of disbursement and repayment of the credits borrowed     

● To understand region/sector wise financial necessity of the countries     


## Datasets

● Source - https://data.worldbank.org/     
● Data size - (rows - 20000, features -34)     
● Main features - loan status, interest rate, effective date, due to ibrd, repaid to ibrd,   original principal amount,etc      
● Data Blending -The original dataset is cleaned and a new dataset with countries and their status as 'Developed' or 'Developing' has been blended for our analysis     


## Steps for execution

● Retrieved the latest available credit disbursal information from the World Bank Organization Statistics     
● Assimilated and evaluated the data that was extracted in the form of a csv     
● Performed data blending with a new dataset     
● Performed data cleaning and normalization     
● Prepared data to be injested into Tableau       
● Introduced calculated field where necessary     
● Created meaningful visualizations to help achieve project goal     



## Tableau Analysis 

1. Began by plotting a geospatial map of developed vs developing nations     
2. Analysed the relation between original principal amount and the amount repaid every year using line graphs for all countries(filter on year)    
3. Identified best repayment patterns displayed by Japan and India     
4. Analysed detailed lending and repayment patterns of Japan and India      
5. Analysed sector wise loan statuses in India and Japan     
(Power and Energy, Road construction showed most no. of completed and repaid projects)     
