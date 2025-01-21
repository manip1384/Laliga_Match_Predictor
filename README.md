# LaLiga Match Predictor

## Overview
The LaLiga Match Predictor is a machine learning project designed to predict the outcomes of LaLiga football matches. The project combines web scraping, data analysis, and predictive modeling to provide insights into match results based on historical data.

## Features
- **Web Scraping**: Collects historical LaLiga match data, including scores, teams, and match dates.
- **Data Preprocessing**: Cleans and processes raw data, handling missing values and feature engineering.
- **Predictive Modeling**: Uses machine learning algorithms to predict match outcomes.
- **Evaluation**: Assesses model performance using metrics like accuracy, precision, and F1 score.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: BeautifulSoup, pandas, numpy, scikit-learn, matplotlib, seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd Laliga_Match_Predictor
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Web Scraping
1. Open the `Webscrapte_Laliga_Matches.ipynb` notebook.
2. Run all cells to scrape and save LaLiga match data to a CSV file.

### Match Prediction
1. Open the `Laliga_Match_Predictor.ipynb` notebook.
2. Load the pre-scraped CSV file.
3. Follow the steps to preprocess data, train models, and evaluate predictions.

## Project Workflow
1. **Data Collection**: Scraped data from reliable football websites using BeautifulSoup.
2. **Exploratory Data Analysis**: Visualized data trends and correlations.
3. **Feature Engineering**: Added features like win/loss streaks, goal differences, and average goals scored.
4. **Model Training**: Trained multiple machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
5. **Evaluation**: Compared models based on accuracy and other metrics.

## Results
- The best-performing model achieved an accuracy of 55% on test data.
- Key features contributing to predictions included goal differences and recent performance trends.




