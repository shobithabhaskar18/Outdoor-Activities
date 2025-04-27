# Outdoor Activities and Adventure Trends Analysis
## Project Overview
- This project analyzes customer reviews and business information related to outdoor recreational activities like hiking, camping, parks, zoos, beaches, and water sports.
- We used Natural Language Processing (NLP) and Sentiment Analysis to extract business insights from Yelp review data.
- The goal is to help businesses and tourism boards understand customer sentiment, identify market trends, and improve service offerings.
## Dataset
- Source: [Yelp Open Dataset](https://business.yelp.com/data/resources/open-dataset/)
- Required Files:
  - business.csv
  - review.csv
- Important:
  - Download the original dataset from the link above.
  - Extract and convert the relevant JSON files (business.json and review.json) into CSV format before running this project.
  - Only the business and review data are used for this project.
  - Reviews from the COVID-19 period (2020–2021) were excluded to avoid bias caused by lockdowns.
## Project Workflow
1. Data Preprocessing:
- Handle missing values.
- Clean and prepare the text data (remove stopwords, lemmatization, punctuation removal).
- Filter businesses and reviews relevant to outdoor activities.
2. Exploratory Data Analysis (EDA):
- Understand review distributions.
- Find top states by number of reviews and ratings.
- Analyze trends across business categories.
3. Sentiment Analysis:
- Apply VADER Sentiment Analyzer to classify reviews as Positive, Neutral, or Negative.
- Explore sentiment trends across different locations and business types.
4. Findings and Insights:
- Top-rated and most-reviewed states identified.
- Key customer concerns extracted.
- Business recommendations based on sentiment patterns.
## Key Insights
- 88% of reviews are positive, showing strong customer satisfaction.
- California and Louisiana lead in customer satisfaction.
- Florida has the highest number of reviews but moderate average ratings.
- Businesses should invest in improving customer service and pricing transparency to boost ratings.
## How to Run
- Clone this repository or download the code.
- Make sure you have the required libraries installed:
  - pip install pandas numpy nltk matplotlib seaborn vaderSentiment
- Download the Yelp Open Dataset and convert business.json and review.json into CSVs.
- Place business.csv and review.csv in the project directory.
- Run the Jupyter Notebook: Outdoor_Activities_Final_Code.ipynb.
- Re-run all cells to:
  - Preprocess the data
  - Perform analysis
  - Generate updated graphs and insights.
## Technologies Used
- Python
- Pandas, NumPy - Data manipulation
- NLTK, VADER - NLP and Sentiment Analysis
- Matplotlib, Seaborn - Visualization