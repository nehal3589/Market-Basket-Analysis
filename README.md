# Instacart Market Basket Analysis

## Introduction
This competition involves a relational dataset describing customer orders over time, with the goal of predicting which products will appear in a user's next order. The database contains over 3 million grocery orders from more than 200,000 Instacart users, providing insights into shopping behavior through the sequence of products purchased in each order. 

## Usage

This dataset can be utilized for various tasks related to market basket analysis, including:

1. *Exploratory Data Analysis (EDA)*:
   - Analyze customer order patterns and visualize shopping behavior over time.
   - Explore the relationships between different products and their frequencies in orders.

2. *Association Rule Learning*:
   - Utilize algorithms such as Apriori to identify frequent itemsets and derive association rules that reveal relationships between products.

3. *Time Series Analysis*:
   - Investigate how ordering patterns change over time, including seasonal effects or trends in product popularity.
  
## Libraries Used

1. **Matplotlib:**  
   A plotting library used for creating static, animated, and interactive visualizations in Python. It provides a flexible way to create various types of charts and graphs.

2. **Seaborn:**  
   A statistical data visualization library based on Matplotlib. It offers a high-level interface for drawing attractive and informative graphics, making it easier to visualize complex datasets.

3. **Pandas:**  
   A powerful data manipulation and analysis library. It provides data structures like DataFrames, which are essential for handling structured data, enabling data cleaning, transformation, and analysis.

4. **mlxtend (Machine Learning Extensions):**  
   A library that provides various tools and extensions for machine learning. The `frequent_patterns` module includes functions like `apriori` and `association_rules` to facilitate the analysis of frequent itemsets and association rule learning.

5. **NumPy:**  
   A fundamental package for numerical computations in Python. It supports a wide range of mathematical operations on large multi-dimensional arrays and matrices, making it an essential tool for scientific computing.

6. **Google Colab:**  
   A cloud-based Jupyter notebook environment that allows you to write and execute Python code in your browser. It provides free access to computational resources and is particularly useful for collaborative data analysis and machine learning tasks.

## Exploratory Data Analysis

### Attributes of the Dataset

- **order_id:** Unique identifier for each order.
- **user_id:** Unique identifier for each user.
- **eval_set:** Indicates the dataset type (e.g., 'prior' for previous orders).
- **order_number:** Sequence number of the order for a user.
- **order_dow:** Day of the week the order was placed (0-6).
- **order_hour_of_day:** Hour of the day the order was placed (0-23).
- **days_since_prior_order:** Days since the last order (NaN if no prior order).
- **product_id:** Unique identifier for each product.
- **product_name:** Name of the product.
- **aisle_id:** Identifier for the aisle where the product is located.
- **department_id:** Identifier for the department the product belongs to.
- **add_to_cart_order:** Order in which the product was added to the cart.
- **reordered:** Indicates if the product was reordered (1 for yes, 0 for no).
- **aisle:** Name of the aisle.
- **department:** Name of the department.

## Links

- [Link to Google Colab](https://colab.research.google.com/drive/1YQgGgKckprF4LIsrvpanpRYJ-4NdjHtn?usp=sharing)
- [Link to Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)

## Credits

This file was created by:
- [Joud Ahmad Al-huthaly](https://github.com/BYXDATA)
- [Nehal Hamed Al-zahrani](https://github.com/nehal3589)
