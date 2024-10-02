# CRUD Operations on Sales Dataset
* This Jupyter notebook provides an example of how to perform CRUD (Create, Read, Update, Delete) operations on a sales dataset using Pandas. This can be useful for understanding how to manipulate datasets in Python, especially in the context of sales or inventory management systems.

# Table of Contents
* Installation
* Project Overview
1. Create
2. Read
3. Update
4. Delete
* Dataset
* Usage
* License
 
# Installation
* To run this project, you'll need to install the required libraries. You can install them using pip:

**pip install pandas jupyterlab**

# Project Overview
**This notebook illustrates how to perform the following operations:**

1. Create
The CREATE operation allows users to add new records to the dataset. In this project, new products (e.g., Laptop, Phone, etc.) are added to a sample sales dataset.

2. Read
The READ operation fetches and displays the dataset, showing existing records such as Product Name, Price, Quantity, and Date of Sale.

3. Update
The UPDATE operation modifies existing records. For example, the price of a phone is updated in the dataset.

4. Delete
The DELETE operation removes specific records from the dataset, such as deleting the entry with ID = 3 (Tablet).

# Dataset
**The dataset consists of a simple CSV file (sales_data.csv) with the following fields:**

* ID: Unique identifier for each sale.
* Product: The name of the product sold.
* Price: The price at which the product was sold.
* Quantity: Number of units sold.
* Date: Date of sale.
  
# Usage
**To use the notebook, simply run the cells in order. The notebook will:**

1. Import necessary libraries.
2. Load a sample sales dataset.
3. Demonstrate how to add, read, update, and delete records.
   
You can also modify the sample data or perform your own CRUD operations by altering the code accordingly.

# License
* This project is open-source and free to use.
