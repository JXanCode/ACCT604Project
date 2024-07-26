# ACCT604Project
The goal of this project was to test various machine learning models for fraud detection. As reference, we used the data from the academic paper by Bao, Ke, Li, Yu, and Zhang called "Detecting Accounting Fraud in Publicly Traded U.S. Firms Using a Machine Learning Approach". 

In addition, we tested on two additional variables: credit ratings and changes in credit ratings. 

The data was sourced from the paper's GitHub repository (https://github.com/JarFraud/FraudDetection/blob/master/data_FraudDetection_JAR2020.csv). In order to decipher the company names and retrieve credit ratings for each of the GVKEY's, we used Compustat Daily Updates-Ratings' database (https://wrds-www.wharton.upenn.edu/pages/get-data/compustat-capital-iq-standard-poors/compustat/north-america-daily/ratings/).


Description of the notebooks:
"DataCleanup_Final": import Original data from reference paper and merge with credit ratings information from Compustat database in WRDS. Also, filter out missing values and export to csv called 'FilteredData_July19".
"genAI": we tried to utilize OpenAI's api for ChatGPT to automatic data processing. We wanted to find the settlement amounts for each fraud case to do further anaylsis. However, we found that the data we got back was not trustworthy as the numbers would change each time we ran it.
"D
