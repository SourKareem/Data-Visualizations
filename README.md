# Data-Visualizations
Here I use primarily Power Bi to create dashboards. I also use Python to get data into Power Bi on the Stock Dashboard, and add a few advanced visuals. My Tweets Dashboard is purely python, using a Streamlit Dashboard.
This is to display my ability to create clear and digestible visuals.

## Cost of Living Dashboad
This was done with a sample dataset form kaggle. I had the question on what country has the lowest cost of living. While there isn't a single aspect to determine that, I used some of the more important metrics. I used groceries, gas, monthly income, rent, and price of a VW and Toyota.
<details>
<summary>Data Cleaning</summary>
I had to clean this dataset because there were missing values from the data so I used Power Query to fill the empty spots with NaN so I could convert the columns to decimal numbers so I could actually visualize them. I also made a few calculated columns like the total grocery cost, and the price of Toyota and VW combined.
</details>
<details>
<summary>Visuals</summary>
I used tables for the groceries because there were so many different groceries to consider. I used Bar Charts for the rent of car price to show the discrepancy between these different places. I then used the stacked bar chart to add some visual variety and used green to match money. I then used the table for gas because I was low on space and it is efficient and easy to read.
</details>
<details>
<summary>Conclusion</summary>
There isn't really a conclusive cheapest cost of living country, but you will see some countries appear in multiple graphs, like Angola. But it does allow the reader to make their own conclusion because they get to decide what categories are more important for them to be cheaper.
</details>

## HR Dashboard
This was done with a kaggle dataset and was to analyze what may cause employee job satisfaction.
<details>
<summary>Data Cleaning</summary>
There was no data cleaning to do for this project
</details>
<details>
<summary>Visuals</summary>
I went with all bar charts for this, which I think normally feels bland and gets boring, but it gives a good sense of how there isn't much correlation with any of the variables and job satisfaction. I think it allows for a quicker conclusion than if I used several different types of visuals. I also have a couple slicers if the company wanted to inquire more about a certain employee or department. I also have cards that show some important statistics about their employees.
</details>
<details>
<summary>Conclusion</summary>
You can see that with work life balance, department, and job involvement, and distance from home, there isn't a very strong correlation. After finding out that there isn't much correlation with job satisfaction, I began to look at how income is affected. You can see that education and time at the company have a direct correlation with income.
</details>

## Sales Dashboard
This was done with a kaggle dataset and the purpose is to evalutate the company's sales by region, product, order size, and customers.
<details>
<summary>Data Cleaning</summary>
There was no data cleaning to do for this project.
</details>
<details>
<summary>Visuals</summary>
I used a decent variety of visuals, using the same stacked bar chart for comparing sales by country and state, a bar chart for the product and year, pie chart for breaking down sales by order size, and a table for customers. I also have 2 slicers for year and product specifically, and a small table for total sales, avg price of sale and total sales.
</details>
<details>
<summary>Conclusion</summary>
You can see that California is where a very huge majority of sales is in California with a bit of sales in other countries and states. Classic cars are their most sold products and medium orders make up the bulk of the sales.
</details>

## Stock Yearly Review
This was done with python API yfinance for Yahoo Finance stock data. I wanted to analyze stock data with a quick dashboard and use some more complex visuals via Python.
<details>
<summary>Data Cleaning</summary>
There was no data cleaning to do for this project.
</details>
<details>
<summary>Visuals</summary>
I used the line chart for the overall price, a bar chart for volume, violin plot for volume as well to see density and max/min. I used a boxplot to get more numbers and analysis on volume and a histogram to see the skew of volume.
</details>
<details>
<summary>Conclusion</summary>
You can see that just below 1 million volume is the most common by a lot. 2020 also had the most volume which could be due to the volatility of that year.
</details>

## Tweets Dashboard
This was done with the help of a guided project to learn these types of dashboards.
<details>
<summary>Data Cleaning</summary>
There was no data cleaning to do for this project.
</details>
<details>
<summary>Visuals</summary>
I used a map visual to see where tweets are coming from geographically, bar charts, and I have a visual to see different tweet examples for each sentiment.
</details>
<details>
<summary>Conclusion</summary>
There isn't much of a problem to solve here, but you do get to see that a lot of tweets are negative which makes sense because most people won't tweet with a regular experience, but an outlier experience like a greate experience or really poor experience will provoke a response out of users.
</details>

