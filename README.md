
# RecoveringSleepingBandit

# Duolingo Multi-Armed Bandit Optimization Algorithm

The project is divided into two parts: paper reproduction and improvement. The reproduction of "A Sleeping, Recovering Bandit Algorithm for Optimizing Recurring Notifications" validated the original study's claims by implementing the Recovering Difference Softmax Algorithm.  This project was built in Python, dataset was posted on the paper. 

This repo consists three python files:
1. data_cleaning.ipynb: This file contains data visualization, historical data process part, and UCB algorithm. 
2. train.ipynb: This file implement the sleeping and recovering algorithm, caculating the arm score for first 15 days as initial arm score for test. 
3.test.ipynb: This file run the two experiments from the paper. 





## Results

Our final test result shows 0.09% increase in average reward compared to the baseline random selection for selecting a notification template.



