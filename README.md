
# Working:
This project is mainly divided into two files:

1. Product insertion in Inventory: In this part, We create a records.json file which contains all the Inventories with details like product id (barcode), name, quantity, price, isAvailable, Expiry date. Here we can add new goods in the inventory and the records will be stored in records.json file.

2. Inventory_Purchase: In this part, 
a) We enter the transaction or purchase details like product id,no. of items purchased,name of customer, mobile number of customer. 
b) If the purchased items are available in inventory, then Bill is generated. 
c) The detailes of the transactions are then stored in sales.json file with attributes like total transactions,transactio id,date,time, product name,total amount of purchase, customer name and customer mobile number.

# Tools required:
1) python - 3.7
2) json

