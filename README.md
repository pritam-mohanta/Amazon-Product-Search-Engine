# Amazon Product Search Engine

This project is an **Amazon Product Search Engine** designed to search for a particular product from a dataset and recommend the product along with some similar products related to it. It specifically uses the **Amazon Electronics Dataset** for its product data.

## Project Overview

1. **Dataset**: We use the **Amazon Electronics Dataset** to search and recommend products.
   
2. **Data Cleaning and EDA**: Perform **data cleaning** and **Exploratory Data Analysis (EDA)** to understand the structure of the dataset.

3. **Text Processing**: 
   - **Natural Language Toolkit (NLTK)**: Used for processing text data.
   - **PorterStemmer**: Helps categorize similar text by reducing words to their root form (stemming).
   - **CountVectorizer**: Converts the processed text into a matrix form for vectorization.

4. **Similarity Calculation**: 
   - **Cosine Similarity**: Used to find the similarity between different products.

5. **Handling Images**: 
   - **Requests**: Used to handle cases where product images are unavailable.

6. **Web Application**: Built using **Streamlit**, which allows users to input product searches and receive recommendations for similar products.

## Tools & Libraries Used

- **Numpy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **NLTK**: 
  - **PorterStemmer**: For stemming text data
- **CountVectorizer**: For text vectorization
- **Cosine Similarity**: To find similarity between products
- **Pickle**: For saving and loading the model
- **Requests**: To handle image unavailability
- **Streamlit**: For building the web application

## Methodology

1. **Data Cleaning**: Clean the dataset to remove inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Perform EDA to gain insights into the data and its structure.
3. **Text Processing**: Use NLTK’s **PorterStemmer** to process the product descriptions and vectorize the text using **CountVectorizer**.
4. **Cosine Similarity**: Calculate the similarity between different products using **Cosine Similarity** to recommend similar items.
5. **Web App**: Build an interactive web app using **Streamlit** to allow users to search for products and view recommendations.

