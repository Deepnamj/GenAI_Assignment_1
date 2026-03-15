Assignment 1 - Data Structure(Lists & Tuples, Sets, Dictionaries, Operations)
# Python Data Structures Assignment

## Overview
This assignment demonstrates the use of **Python lists, tuples, sets, and dictionaries** through four tasks. Each task builds on the previous one to show dynamic handling of products, prices, and categories.  

The notebook format allows running code **cell by cell** and viewing outputs directly below the code.

---

## Tasks

### **Task 1: Lists and Tuples**
- Create a **list of products**.
- Create a **tuple** for a sample product `(product_name, price, category)`.
- Access and print the 2nd and last product.
- Append new products to the list.
- **Extra:** Convert tuple to list, update price, and convert back to tuple.
- **Key concepts:** list indexing, list append, tuple immutability, type conversion between tuple and list.

---

### **Task 2: Sets**
- Create a **set of unique categories** for products.
- Add new categories (demonstrates that duplicates are ignored).
- Check if a category exists in the set.
- Count the total number of unique categories.
- **Key concepts:** set creation, uniqueness, membership checking, adding elements.

---

### **Task 3: Dictionaries**
- Create a **price dictionary** with product names as keys and prices as values.
- Add a new product and update existing prices.
- Remove products safely with error handling.
- Calculate average price and find the product with max/min price.
- **Key concepts:** dictionary operations (`add`, `update`, `pop`), arithmetic with dictionary values, defensive programming.

---

### **Task 4: Catalog and Category Mapping**
- Dynamically create a **catalog**: a list of tuples `(product_name, price, category)`.
- Build a **category-to-products dictionary** mapping each category to its products.
- Find and print products in the category with the **maximum number of items**.
- **Key concepts:** list comprehension, dictionary construction, iterating through tuples, dynamic mapping, max function.

---

## How to Run

1. Make sure you have **Python 3.x** and **Jupyter Notebook** or **Jupyter Lab** installed. You can install it via:

   ```bash
   pip install notebook
   
2.Save the notebook file as assignment.ipynb.

3.Open a terminal/command prompt, navigate to the folder containing the notebook, and start Jupyter:

  ```bash
  jupyter notebook

or
  ```bash
  jupyter lab

4.In the browser window that opens, click on assignment.ipynb to open the notebook.

5.Run the notebook cells sequentially by:
   Clicking Run in the toolbar for each cell, or
   Pressing Shift + Enter to execute a cell and move to the next.

6.All outputs for Tasks 1–4 will appear directly below each cell.   
