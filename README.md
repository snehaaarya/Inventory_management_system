#Inventory_management_system

**Basic Inventory Management System using Python and Json**

In this Folder there are two json file one for storing the inventory records and other to store the available stock ie. record.json and stock.json respectively

In **IMS.ipynb** file it allows to add prducts and its details which are then stored into the **record.json file**.

In **sales.ipynb** file it allows to store the available quantity of the particular product after the sales which is stored in stock.ipynb file.

In **sales.ipynb** user input is taken in which the products they wish to buy is inputed and their particular details are displayed and **bill is generated**.

The **prod_id** stored in the json files are **unique**. 

A function is included in which it checks if the prod_id inputed by the user is present in records.json or not if no it display "invalid ID!"

The **Prod_id** is unique **4-digit** number and **starts from 1001**.
