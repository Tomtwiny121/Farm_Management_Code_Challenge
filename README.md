# Farm_Management_Code_Challenge


Certainly! Below is the formatted README file with the provided information:

markdown
Copy code
<div align="center" style=" font-size: 80%; text-align: center; margin: 0 auto">
    <img src="https://raw.githubusercontent.com/Explore-AI/Pictures/master/Python-Notebook-Banners/Code_challenge.png"  style="display: block; margin-left: auto; margin-right: auto;"/>
</div>

# Code challenge: Farm harvest management
© ExploreAI Academy

In this code challenge, we will assist a farmer in calculating the total harvest from two fields (wheat and potatoes) and the overall expenses and profits for this season.

## Learning objectives
In this train, we will:
- Understand how to perform basic arithmetic operations in a Jupyter notebook.
- Know how to assign numerical values to variables.
- Know how to use the print() function to display our results.

## Instructions
- **This code challenge does not count for marks.**
- Do not add or remove cells in this notebook.
- Answer the questions according to the specifications provided.
- Use the given cell in each question to see if your function matches the expected outputs.

## Challenge 1
Calculate the total harvest for the farmer.

```python
total_kgs_wheat_harvest = 2050
total_kgs_potato_harvest = 3600

total_kgs_harvest = total_kgs_wheat_harvest + total_kgs_potato_harvest
print("Total harvest in kilograms:", total_kgs_harvest)
Expected outputs:

python
Copy code
Total harvest in kilograms: 5650
Challenge 2
Calculate the total expenses (in dollars) and print the result.

python
Copy code
seed_expense = 650
labour_expense = 3070

total_expenses_dollars = seed_expense + labour_expense
print("Total expenses in dollars:", total_expenses_dollars) 
Expected outputs:

python
Copy code
Total expenses in dollars: 3720
Challenge 3
Calculate the total revenue (in dollars) and print the result.

python
Copy code
price_per_kg_wheat = 2
total_kgs_wheat_harvest = 2050
price_per_kg_potato = 1.4
total_kgs_potato_harvest = 3600

total_revenue_dollars = ((price_per_kg_wheat * total_kgs_wheat_harvest) + (price_per_kg_potato * total_kgs_potato_harvest))
print("Total revenue in dollars:", total_revenue_dollars) 
Expected outputs:

python
Copy code
Total revenue in dollars: 9140
Challenge 4
Calculate the total profit (in dollars) and print the result.

python
Copy code
total_profit_dollars = total_revenue_dollars - total_expenses_dollars
print("Total profit in dollars:", total_profit_dollars)
Expected outputs:

python
Copy code
Total profit in dollars: 5420 
<div align="center" style=" font-size: 80%; text-align: center; margin: 0 auto">
    <img src="https://raw.githubusercontent.com/Explore-AI/Pictures/master/ExploreAI_logos/EAI_Blue_Dark.png"  style="width:200px";/>
</div>
```
