# SQL Usage on the Northwinds Trading Dataset  

## Introduction to Problem
I was presented with an opportunity to practice SQL Queries, Pandas DataFrames, Visualizations, and Hypothesis Testing using the fictitious North Wind Company. I was asked to investigate four hypotheses- the first was given and the other three were based on exploratory data analysis.  

## Introduction to Files
* Northwind_small.sqlite - The raw data for the North Wind Company
* northwind_erd.png - The ERD associated with the raw data
* Module 3 Project.gslides - A brief Google slides presentation overviewing conclusions  
## Introduction to Hypotheses Conducted
### Overarching question: How can we maximize sales in specific regions?
* Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?
* Is there a higher probability of buying one certain category in certain regions?
* Where are they sold most and would a discount affect these sales?
* Is there a region of employees who are maximizing sales for the company?  
## Conclusions Drawn
* Across the board, a 5% discount is statistically more effective than a 25% discount. I would recommend using a 5% discount where appropriate, rather than a 25% discount.
* The highest performing category was dairy products. With that in mind, the different regions were tested and it was found that North America and Western Europe were the highest consumers of dairy products. Southern Europe was the lowest. My recommendation would be to increase stock in North America and Western Europe.
* Of these regions, it was researched where a discount may be most effective to maximize sales. It is recommended that a 15% discount be implemented in Western Europe where sales are already high. However, in North America and Southern Europe, based on current data, it was not found to be statistically significant to implement a discount.
* Both of the regions that North Wind operates out of where found to have statistically similar amounts of sales. I do not recommend any coaching for a specific region.