Sephora Data Strategy Analysis

Mock CIO Interview Project — Business Data Analyst Portfolio

A multi-part data analysis project developed as part of a mock Chief
Information Officer intea-driven decisions canimprove product strategy, brand performance, and customer experience at
Sephora.

Project Overview

This project analyzes Secustomer review dataacross three distinct analytical approaches, combining descriptive statistics,
correlation analysis, ang (NLP) to surfaceactionable business insights.

Analyses

1. Brand & Product Performance (sephora_brand_product_performance.ipynb)

Identifies Sephora's top and bottom performing products and brands by customer rating. Applies review volume filtering to ensure statistical reliability,and visualizes results with horizontal bar charts. Also explores the relationship between product rating and customer engagement (loves count).

2. Price vs. Rating Correlation (sephora_price_rating_correlation.ipynb)

Examines whether higher-priced products receive better customer ratings.Calculates the Pearson correlation coefficient between price and rating across the full product catalog and visualizes the relationship with a scatter plotand trend line.

3. Cross-Product Compatibility (sephora_cross_product_compatibility.ipynb)

Uses NLP keyword extraction (FlashText) to scan thousands of customer reviews and identify which products are frequently mentioned together. Surfacesproduct pairing patterns that can inform bundling strategies, recommendations, and shelf placement decisions.

Technologies Used

- Python 3
- pandas
- matplotlib
- NumPy
- FlashText (NLP keyword extraction)

Presentation

A full walkthrough of the analysis and business recommendations is availablevia Loom:
