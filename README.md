# Problem Statement
Explore and identify different segments present in the customer transaction data.
DataSet
The dataset contains transactions on an e-commerce website between the period Feb 2018 to Feb 2019 from customers across different countries. 

# Dataset  
https://drive.google.com/file/d/1m1H51SB2C9CZ6xr29bgSgfQ231bYSv1m/view?usp=sharing


# Columns

 UserId - Unique identifier of a user.

TransactionId - Unique identifier of a transaction. If the same TransactionId is present in multiple rows, then all those products are bought together in the same transaction.

TransactionTime - Time at which the transaction is performed

ItemCode - Unique identifier of the product purchased

ItemDescription - Simple description of the product purchased

NumberOfItemsPurchased  - Quantity of the product purchased in the transaction

CostPerItem - Price per each unit of the product

Country - Country from which the purchase is made.

Size of data (1.08 Million x 8)


# Final output
![newplot](https://user-images.githubusercontent.com/53363478/119251395-f518eb80-bbc3-11eb-8218-dfe3cbd7ce1c.png)

After Preprocessing and Clustering , all data was tranformed into these 3 columns/dimensions. 

Recency - How recently the customer has made the purchased (Lower the better)

Frequency - How frequently the customer has made the purchased (Higher the better)

Monetary - How much was the total amount of all transactions (Higher the better)

# Observations 
1. Customers in Yellow cluster are core customers since they have low recency , high frequency and high monetary values.

2. Then comes customers in Purple cluster even if they have high recency value but their frequency and monetary values are high.

3. Then comes customers in Orange cluster even almost same recency value as that of Purpple and  their frequency and monetary values are bit less than Purple customers.
