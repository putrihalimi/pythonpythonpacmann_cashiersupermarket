# pythonpythonpacmann_cashiersupermarket
 cashier friendly

 # Supermarket Super Cashier Friendly 
## membuat sistem kasir yang self-service di sprmrkt

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
PPT Super Cashier by Salsabila Putri Halimi
https://www.canva.com/design/DAFzMVAY97Y/QvEkTku8lFp41PV-cNBTxg/edit?utm_content=DAFzMVAY97Y&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Tugas Project dari Pacmann tentang kasus membuat sistem kasir yang ramah di supermarket.

- Notebook Jupyter (Phyton) ✔
- Canva ✔
- Youtube ✔

## Background Problem Statement

Andi, the owner of a large supermarket in Indonesia, wants to streamline the business process by implementing a self-service cashier system in her supermarket. The goal is to allow customers to input items, quantities, and prices directly, enabling customers who are not physically present in the city to make purchases remotely. The challenge is to develop a user-friendly and efficient self-service cashier system.


## Requirements/Objectives

- Membuat kerangka transaksi
- Membuat ID transaksi customer
- Memasukkan nama_item, jumlah_item dan harga_barang
- Menghapus salah satu i atau menghapus semua transaksi
- Pengecekan transaksi apakah sudah benar
- Menghitung total belanjaan customer

>Code Requirements:
Modular and clean code following PEP8 standards.
Well-documented functions and classes explaining their functionalities, parameters, and usage examples.
Implementation of try-except blocks for error handling and defensive programming.
Utilization of Python libraries or methods for efficient calculations.

>Explanation of the functions (methods) and attributes created within the Transaction class and their functions in the context of a self-service cashier system :
- Attributes (Properties):
[transaction_id]: This attribute stores the transaction ID. The transaction ID is used to uniquely identify each transaction.
[items]: This attribute is a list that stores information about each item in the transaction. Each item is represented as a dictionary including the item's name, quantity, and price per item.
[total_amount]: This attribute stores the total amount of the purchase in the transaction, calculated based on the quantity and price per item of all items in the items list.
- Methods:
set_transaction_id(self, transaction_id): This function is used to set the transaction ID. Users can call this function to initialize the transaction ID when creating a new transaction.
add_item(self, item_name, quantity, price_per_item): This function allows users to add an item to the transaction. Users must provide the item's name, quantity, and price per item. The function calculates and updates the total_amount based on the added item.
delete_item(self, item_name): This function enables users to delete an item from the transaction based on the item's name. The function reduces the total_amount based on the removed item.
update_item_quantity(self, item_name, updated_quantity): This function allows users to update the quantity of an item in the transaction based on the item's name. The function updates the item's quantity and the total_amount according to the quantity change.
update_item_price(self, item_name, updated_price): This function enables users to update the price per item of an item in the transaction based on the item's name. The function updates the item's price per item and the total_amount according to the price change.
check_order(self): This function is used to check the order before confirming the purchase. It verifies if there are any input errors in the transaction items. If there are errors, the function returns an error message. If there are no errors, the function returns the transaction details.
total_price(self): This function calculates the total purchase amount after applying discounts according to the predefined rules.
get_transaction_details(self): This function returns comprehensive details of the transaction, including the transaction ID, items in the transaction, and the total purchase amount.

Each function and attribute is designed to facilitate self-service transaction operations in the cashier system, allowing users to add, remove, update items, check orders, calculate total purchases, and obtain transaction details with ease. These functionalities contribute to creating an efficient and convenient shopping experience for customers.

## Flow Chart
penjelasan alur code
link : https://drive.google.com/file/d/13m9LRgqd8oOdrfNJsnl9NO_O4MkZfIsZ/view?usp=sharing

##### Bisa demostrasikan syntax python studi kasus Super Cashier - Supermarket
https://drive.google.com/file/d/1ke2ylu5COveFfKoTX2tYx40aMPNLpPIX/view?usp=sharing

## Credit 
by. Salsabila Putri Halimi
Get in touch with LinkedIn, Instagram and Tiktok

