# Market Basket Analysis.

This repository contains an implementation of a market basket analysis for a store focusing on items from their Stationary and Health & Beauty Aids departments. Using the provided transaction data, the project explores the purchasing relationships of seventeen products over a three-month period.

## About the Project

The project involves analyzing the `transactions.csv` data file which contains information on 200,000 transactions made over a three-month period. The file has two columns – the transaction id (Transaction) and the product purchased (Product), and contains over 400,000 rows. Seventeen products are represented in the data set: bar soap, bows, candy bars, deodorant, greeting cards, magazines, markers, pain relievers, pencils, pens, perfume, photo processing, prescription medications, shampoo, toothbrushes, toothpaste, and wrapping paper.

As in charge of these departments, the aim is to discover the relationships between different products bought together and to use these relationships strategically in various ways. 

## Potential Applications of the Analysis

1. **Targeted Marketing**: Pair the transactions with customer data to improve marketing efforts, enabling targeted mailings/email suggestions.
2. **Pricing Strategy**: Adjust the price and profit margins together. One item could be put on sale while increasing the price of the other.
3. **Product Placement**: Place highly correlated items closer while displaying them on shelves. For example, toothpaste and candy bars, greeting cards, candy bars, and magazines, perfume and toothbrushes, etc.
4. **Sales Bundling**: Bind highly associated products in the sales process by providing some percentage of discounts to customers who buy the associated items in a set.
5. **Partnership with Banks**: Partner with banks to give customers cashback on their purchase of highly associated products.
6. **Membership and Rewards Programs**: Start a membership and rewards program based on these associations.

This repository contains all the code and resources to perform the above analysis and implement these strategies based on the findings. It represents an important step in improving the marketing and sales strategies of the store.

## Dataset

The `transactions.csv` file contains information on 200,000 transactions made over a three-month period. Each row involves a single product, and transactions involving multiple products span multiple rows.

## Technologies Used

This project is implemented using Python, and makes use of the following libraries:

- os: to interact with the operating system.
- numpy: for numerical computations.
- pandas: for data manipulation and analysis.
- mlxtend: for the implementation of apriori algorithm and association rules.
- sklearn: for preprocessing of the dataset.
- matplotlib: for data visualization.

## Results and Takeaways

Comparing the rule lists using different criteria, the metrics referring to lift seems preferable to the others. But since the lift measures co-occurrences only, and conviction gives us the measure of the information of the absence as well, we will first sort by lift and then conviction. The final insights from this project provide strategic directions for marketing, sales, product placement, and pricing:

1. Pair the transactions with customer data, to improve marketing efforts, enabling targeted mailings/email suggestions.
2. Adjust the price and profit margins together. One item could be put on sale while increasing the price of the other.
3. Place highly correlated items closer while displaying them on shelves.
4. Bind highly associated products in the sales process by providing some percentage of discounts to customers who buy the associated items in a set.
5. Partner with banks to give customers cashback on their purchase of highly associated products.
6. Start a membership and rewards program based on these associations.
