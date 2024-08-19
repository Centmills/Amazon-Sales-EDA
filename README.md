# Amazon Sales Data Analysis-Python

## Project Overview

This project involves analyzing Amazon sales data to gain insights into sales performance, product popularity, customer sentiment, and more. Data visualization techniques are used to present the findings effectively.

## Data Description

The dataset used for this analysis includes the following columns:

- **product_id**: Unique identifier for each product.
- **product_name**: Name of the product.
- **category**: Category to which the product belongs.
- **discounted_price**: Price of the product after discount.
- **actual_price**: Original price of the product before discount.
- **discount_percentage**: Percentage discount applied to the product.
- **rating**: Average customer rating of the product.
- **rating_count**: Number of ratings the product has received.
- **about_product**: Description or details about the product.
- **user_id**: Unique identifier for each user.
- **user_name**: Name of the user.
- **review_id**: Unique identifier for each review.
- **review_title**: Title of the review.
- **review_content**: Full content of the review.
- **img_link**: URL link to the product image.
- **product_link**: URL link to the product page.

## Python Libraries Used
The following Python libraries were imported:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `wordcloud`
- `textblob`
- 
## Project Structure

The project consists of several key components:

1. **Data Cleaning and Preprocessing**: 
    - Handling missing values.
    - Data type conversion.
    - Checking for duplicates
    - Calculating total revenue.

2. **Analysis and Visualization**:
   The following were determined:
    - Total revenue for each product was calculated
    - Top 10 products by total revenue
    - Sales distribution by category
    - Correlations between discount percentage, rating count & total revenue
    - Number of ratings per category
    - Distribution of ratings across products
    - Most frequently mentioned keywords in reviews
    - Sentiment analysis on reviews
    - Sentiment distribution
    - Number of reviews per category
    - Number or reviews per user
    - Percentage of products with valid image links
    - Average rating by category  

Bar charts, pie charts, histograms, word clouds, and heatmaps are used to visualize the analysis results.

## Sample Visualization (More on Notebook)
![image](https://github.com/user-attachments/assets/f0102a3e-7bac-4596-8ccf-643ed109f4b3)

![image](https://github.com/user-attachments/assets/594e3d4f-380f-484a-9ece-69dcfbf15ccc)

![image](https://github.com/user-attachments/assets/e90c8d78-9341-44cf-ab05-148da7068ba6)

## Conclusion
This project serves as a comprehensive analysis of Amazon sales data, offering a detailed look into various aspects of product performance and customer behaviour. The insights gained can help in making data-driven decisions for improving sales strategies, customer satisfaction, and overall business performance. 
  

