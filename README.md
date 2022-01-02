# Preprossing-loan-data-with-NumPy
In this project, I have cleaned and pre-processed the loan data that belongs to an affiliate bank based in the United States. This cleaning process is done using the NumPy library of Python.
This cleaned data will be used to create a credit risk model which estimates the probability of default for every personal account.
When we're measuring credit worthiness, we need to be extremely risk averse and distrustful of any unavailable data. That's why the consensus in the field is that missing information suggests foul play because loan applications are self-reported to elaborate since candidates fill out their loan applications manually. There is an incentive to withhold information which can lower their chances of getting a loan. Of course, we prefer to give out loans to applicants who can repay them so that the information isn't available we will just assume the worst and mark that field as ‘red_flag’ for further analysis and convenience in the model building phase. However, what is worst varies from one column to the next.
All the values are in dollars, so we need to provide their euro equivalents.
Every categorical variable must be quantified. So we need to change any text columns into numbers based on the information they contain. 
All the other tasks are explained in the jupyter notebook.
