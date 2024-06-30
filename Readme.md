

# Seattle Airbnb Data Analysis

## Overview

This project aims to explore the Seattle Airbnb dataset to answer three key questions:
1. What factors most influence the price of Airbnb listings in Seattle?
2. How can we predict the occupancy rate of a listing based on its features?
3. What is the general sentiment of the reviews, and how does it correlate with the overall rating of a listing?

The project follows the CRISP-DM process and includes data cleaning, exploratory data analysis, modeling, and sharing insights.

## Dataset

The dataset consists of three main files:
- `listings.csv`: Detailed information about Airbnb listings in Seattle.
- `reviews.csv`: Comments left by guests who stayed at the listings.
- `calendar.csv`: Availability and pricing information for each listing.

## Requirements

- Python 3.6+
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install the required packages using:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Data Cleaning and Preprocessing

The following steps are performed to clean and preprocess the data:

1. Handle missing values by filling numerical values with the median and categorical values with the most frequent value.
2. Drop columns with more than 20% missing values.
3. Convert price data to numerical format.
4. Normalize numerical features.
5. Encode categorical variables.

## Analysis and Modeling

### Pricing Analysis

A regression model is built to identify the factors that most influence the price of Airbnb listings in Seattle.


### Sentiment Analysis

Sentiment analysis is conducted on the review texts to determine the general sentiment and its correlation with the overall rating of a listing.


## Conclusion

This project provided valuable insights into the factors influencing Airbnb listings in Seattle. By leveraging data science techniques, we identified key factors affecting listing prices, predicted occupancy rates, and analyzed review sentiments. These findings can help Airbnb hosts optimize their listings and provide better experiences for guests.

Feel free to reach out with any questions or comments. Happy hosting and traveling!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Kaggle for providing the Seattle Airbnb dataset.
- scikit-learn for providing excellent machine learning tools.
- matplotlib and seaborn for visualization libraries.

---

This `README.md` provides an overview of the project, instructions on how to set up and run the analysis, and details on each step of the process. Feel free to adjust it to better suit your needs or to include any additional information.