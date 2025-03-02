# Product-Segmentation
Data Analysis and K-Means clustering on 2400+ product variants from Amazon, Flipkart, Ulta, Sephora to help formulate startegies for a new cosmetic company entering the cosmetic market.

## Data Overview

- Product_name : The name of the product.
- Href : The URL of each product.
- Price : The price of the product in INR.
- Brand : The brand of each product.
- Ingredients : The ingredients of each product.
- Form : The consistency of the product.
- Type : Additional information about the product.
- Color : The color of product.
- Quantity : The volume of product in ml.
- Category : The category of cosmetic product. (eyes, face, lips, body, skincare, or hair)
- Subcategory : The sub-category of the product.
- Rating : The customer rating of the product. (0 to 5)
- Number of ratings : The number of customers who rated that product.
- Website : The website it is scraped from. (Ulta, Amazon, Flipkart, or Sephora)

## K-Means clustering

![image](https://github.com/user-attachments/assets/917dff6f-f362-4c32-90d2-e3a6ae0be5f0)

### Key Observations

![image](https://github.com/user-attachments/assets/4bba95af-c642-4ac0-a201-48b0bca630f1)

### Identified 3 main market segments - 
1. Essential Makeup - With the largest no. of distinct products, this segment offers diverse options of essential makeup products for consumers. Despite being priced towards the lower end, these products provide good value for money due to their small size, making them accessible to a broader audience.


2. Luxury Fragrances - The number of products is relatively small, but they command higher prices with high ratings, reflecting their premium positioning. Consumers are willing to invest in these high-quality fragrances, considering them as luxury items or special treats. This is particularly a niche market.


3. Skincare and Bodycare Essentials - Encompassing a comprehensive range of skincare and body care solutions, they are priced towards the lower end. Their larger size reflect their functionality and value for consumers, contributing to their high ratings. They cater to consumers seeking effective and affordable solutions for their skincare and grooming needs.

## Regression - Features with High Correlation with Price

### Observations
- Global Products: Generally positive impact.
- Local Products: Mixed impact, generally negative.
- Number of Ratings: Small coefficients, not a significant impact on price.
- Product Size: Positive coefficient for face, negative for skincare and negligible for others.

- Review Count not a factor in Pricing Strategy by brands: The number of ratings has a minimal impact on pricing across
categories. Suggests that the volume of feedback doesn't significantly
drive price changes.
- Product Size: For face, there’s a positive correlation, suggesting larger sizes may be
priced higher.
- In other categories, there’s a negative or negligible correlation,
indicating that larger sizes might not always command higher prices
and might even be priced lower, possibly due to bulk pricing
strategies.
- Global vs Local Products: Global products tend to have a positive influence, whereas local
products show mixed results. Need to strengthen the global product offerings
and tailor local products to better meet regional demands.


