# British Airways Customer Review Analysis

This repository contains a Jupyter Notebook that performs an exploratory data analysis (EDA) of British Airways customer reviews. The analysis aims to understand customer satisfaction, identify key factors influencing reviews, and uncover potential areas for improvement for the airline.

## Dataset

The dataset used for this analysis is "British_Airway_Review.csv". It contains customer reviews and associated information such as date, country, seat type, recommendation, star rating, route, and type of traveler.

## Analysis Steps

The Jupyter Notebook performs the following analysis steps:

1. **Data Loading:** Loads the dataset into a pandas DataFrame.
2. **Data Exploration:** Explores the dataset's structure, including the number of rows and columns, data types of each column, and the presence of missing values. It also examines the distribution of key variables.
3. **Data Analysis:** Performs more in-depth analysis, including identifying potential outliers and relationships between variables.
4. **Data Visualization:** Creates visualizations to gain insights into the distributions of key variables and potential relationships.

## Key Findings

* **Data Overview**: The dataset contains 2500 customer reviews with 8 variables. No missing values were detected.
* **Star Ratings**: The average star rating is 4.27, ranging from 1 to 9.
* **Review Length**: Average review length is approximately 930 characters.
* **Date Analysis**: Reviews are analyzed by month to identify potential trends.
* **Categorical Variables**: Analysis of categorical variables reveals the most frequent categories.
* **Relationships between variables**: Visualizations explore relationships between 'stars' and other variables.

## Insights and Next Steps

* **Deepen Sentiment Analysis**: Conduct a more comprehensive sentiment analysis of the reviews using advanced NLP techniques.
* **Investigate Trends and Seasonality**: Further explore the relationship between date and star ratings to identify potential trends or seasonality.

## Usage

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook environment.
3. Run the cells in the notebook to perform the analysis.
4. Explore the visualizations and findings.

## Dependencies

The notebook uses the following libraries:

* pandas
* matplotlib
* seaborn

Make sure you have these libraries installed before running the notebook. You can install them using `pip install pandas matplotlib seaborn`.

## Contributing

Contributions are welcome! Please feel free to open issues or pull requests for any improvements or suggestions.

## License

This project is licensed under the [MIT License](LICENSE).
