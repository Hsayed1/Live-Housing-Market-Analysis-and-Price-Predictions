Notebook Link: https://colab.research.google.com/drive/1kyEhvbyeyDWGeWYwOOLy6ix8eXsuUPkF?usp=sharing
# Housing Market Analysis and Price Prediction

## Project Overview
This project examines the New York housing market using data from two sources: the Kaggle New York Housing Market dataset and the Zillow Scraper API from Scrapeak.com. The analysis includes data cleaning, feature engineering, exploratory data analysis, and machine learning modeling to predict housing prices based on various factors.

## Data Sources
- **Kaggle New York Housing Market dataset:** Provides extensive data on houses for sale in New York.
- **Zillow Scraper API:** Used to scrape additional listings across different New York counties, offering a more comprehensive view of the housing market.

## Project Steps

### Data Acquisition
1. **Kaggle Dataset:** Download and extract the New York Housing Market dataset from Kaggle.
2. **Zillow Scraper API:** Use the API to scrape live housing listings from various New York counties.

### Data Preprocessing
- Clean and preprocess both datasets by removing duplicates and irrelevant columns.
- Perform feature engineering, including extracting city information from addresses and associating counties where necessary.
- Merge the two datasets, retaining a column to specify the data source.

### Exploratory Data Analysis (EDA)
- Use Seaborn and other visualization tools to examine trends and insights within the data.
- Generate interactive plots using Folium to visualize property listings across different counties.

### Machine Learning Models
- **Models Used:**
  - Convolutional Neural Network (CNN)
  - Support Vector Regression (SVR)
  - Gradient Boosting Regression (GBR)
- **Model Training:**
  - Build and train models using cleaned data.
  - Perform hyperparameter tuning and feature selection to improve model performance.
  - Evaluate models using test data.

## Results
- **Visualization:** Interactive maps and plots showing property distributions and price trends.
- **Model Performance:**
  - CNN: 45% accuracy
  - SVR: 4.5% accuracy
  - GBR: Best performance with 75% accuracy

## Challenges
- Limited by free API usage credits.

## Future Improvements
- Upgrade API accounts for more comprehensive data scraping.
