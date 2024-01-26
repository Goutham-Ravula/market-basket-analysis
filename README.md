# Market Basket Analysis using Apriori Algorithm

![License](https://img.shields.io/badge/license-MIT-blue)

## Overview

This project focuses on performing Market Basket Analysis using the Apriori algorithm. Market Basket Analysis is a technique commonly used in retail and e-commerce to discover associations and relationships between products purchased by customers. The Apriori algorithm is employed to efficiently mine frequent itemsets and generate association rules from transaction data.

## Dataset

The project utilizes a dataset from a retail market, containing information about member numbers, dates, and item descriptions of products purchased. The dataset can be accessed on [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset).

## Exploratory Data Analysis (EDA)

The initial phase involves exploratory data analysis to understand key aspects of the dataset:

- Visualizing the total number of items sold by date using a scatter plot.
- Analyzing daily and monthly statistics, including unique items, total items sold, and average items sold per day.

## Data Visualization

Various data visualization techniques are employed to provide insights:

- Line plot showcasing the total number of items sold by month.
- Bar plot illustrating the distribution of item counts for different products.
- Exploratory scatter plots and matrix graphs to visualize association rules.

## Association Rule Mining with Apriori

The Apriori algorithm is applied to discover association rules between products. Key parameters include:

- Minimum Support: 0.001
- Minimum Confidence: 0.05
- Minimum Lift: 1.2

The results provide information on frequent itemsets, support, confidence, and lift for discovered association rules.

## Results and Visualization

The project concludes with detailed visualizations of association rules:

- A scatter plot depicting association rules based on support, confidence, and lift.
- A grouped matrix graph providing a comprehensive view of product associations.
- A parallel coordinate graph illustrating the strength of association rules.

## Usage

Feel free to explore, modify, and utilize this project for your own analysis. The code and visualizations can be adapted for other datasets or retail scenarios.

## Dependencies

- Python 3.x
- Libraries: pandas, apyori, matplotlib, plotly, numpy

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
