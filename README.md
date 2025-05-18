# World's Largest Collection of Tinned Seafood
🐟🐠🎣

## Goal
Rainbow Tomatoes Garden says it has the world's largest tinned seafood collection, with over 800 products from 27 countries. Are there patterns to be drawn from its pool of data, that might be useful for consumers when they shop for tinned fish? 

## Findings
After some [analysis](Tinned-Fish.ipynb), I was surprised by how many countries tinned fish come from and how many kinds of tinned products are out there. Spain, Portugal and France are the biggest tinned seafood producers, but there are also products from Armenia, Korea and Canada. There are regular fish options like tuna and sardine, but there are also tinned garfish and mussels. I looked more into how different countries and different type of fish differ in size and price, and ended up focusing my analysis on which tinned fish from which country has the cheapest unit price.
<br>Read my [article](https://tiff-xwang.github.io/tinned-fish/) to find out!</br>
 
## Data & Workflow
I used Rainbow Tomatoes Garden's [spreadsheet](Rainbow Tomatoes Garden Fish List.csv) that contains all the information about each product.

First, I counted how many types of product there are and chose to focus on a few types of fish that are popular ingredients and are well-represented in the dataset -- mackerel, anchovy, sardine and tuna. I also counted the number of countries and the number of products from each country.

Then, with different combinations of fish and country, I calculated the median price and median tin size, like sardine from Spain vs. sardine from France, or mackerel from Portugal vs. mackerel from Spain. I also looked into the type of oil used.

From there, I was able to compile a [list](unit_price.csv) of the most high-producing countries of the four types of fish and the average unit price of each of those countries' fish.

## Things learned
I crafted my visualizations with the consumers in mind. What is the clearest way for them to get shopping tips from my article? What are the most relevant tips for someone shopping for tinned fish? These are the questions I considered for the presentation of the data.


