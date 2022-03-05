# Cryptocurrencies

## Project overview

The pruporse of this project is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for an investment. To acommplish this, the data was processed to fit the machine learning models. Since there was no known output, this project used unsupervised learning. Also, to group the cryptocurrencies, a clustering algorithm was used. Finally the results were shown with data visualizations to share findings.

## Resources

- Data Source: `crypto_data.csv` (https://min-api.cryptocompare.com/data/all/coinlist)
- Data Tools: `Pandas`, `hvPlot`, `scikit-learn`
- Software: `Jupyter Notebook`

## Results

### Preprocessing the Data for PCA

Data was not ideal and needed to process it to fit the machine learning models. The data was processed by only keeping the cryptocurrencies that are being traded, droping a few columns, removing rows that had at least one null value and keeping only rows where coins have been mined.

![image](https://user-images.githubusercontent.com/91766276/156902253-f6988d1b-6abd-4f7b-8528-58a2db180cc3.png)

![image](https://user-images.githubusercontent.com/91766276/156902359-480f7748-b88a-4521-9810-4f69caa8ee1a.png)

Used the `get_dummies()` method to create variables for the two text features, Algorithm and ProofType, and stored the resulting data in a new DataFrame named `X`.

![image](https://user-images.githubusercontent.com/91766276/156902430-b02a44fa-7c1f-4dae-a6d1-96ab42d4f693.png)


![image](https://user-images.githubusercontent.com/91766276/156900059-96198cfd-8fbb-4b70-99c2-cb49be8f4f54.png)


![image](https://user-images.githubusercontent.com/91766276/156900074-b8ba9661-b929-4fd6-9656-0a518430cc09.png)



![image](https://user-images.githubusercontent.com/91766276/156900086-5fb12606-a879-4896-8472-35302906bf7c.png)




![image](https://user-images.githubusercontent.com/91766276/156900110-3f934c9b-f106-49f1-b5ba-06d018b55802.png)




![image](https://user-images.githubusercontent.com/91766276/156900121-50068575-22ec-474e-a3f2-ccf60356db41.png)
