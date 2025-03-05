# Amazon-Fashion-Discovery-Engine
Build a recommendation engine which suggests similar products (apparel) to the given product (apparel) in any e-commerce websites.

# Overview
This project retrieves apparel data using the Amazon Product Advertising API and applies NLP techniques to recommend similar products.

# Key Steps
Data Collection: Fetch product details via API.
Preprocessing: Clean data, handle missing values, and apply text processing.
Feature Engineering: Use BoW, TF-IDF, and Word2Vec for text similarity.
Enhancements: Incorporate brand & color for better recommendations.

# Tech Stack
Python, Amazon API, NLP (TF-IDF, Word2Vec), Pandas, Scikit-learn