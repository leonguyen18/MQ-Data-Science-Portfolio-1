# COMP6200 Data Science - Portfolio 1: Analysis of an E-commerce Dataset

This project is part of the COMP6200 Data Science unit. It involves the analysis of a combined E-commerce dataset where each user can post a rating and review for the products they purchased. Other users can evaluate the initial rating and review by expressing their trust or distrust.

![Dataset Description](./Fig1%20The%20Combined%20E%20commerce%20Dataset.png)

## Dataset

The dataset includes comprehensive information for each user, such as their profile, ID, gender, city of birth, product ratings (on a scale of 1-5), reviews, and the prices of the products they purchased. Moreover, for each product rating, we have information about the product name, ID, price, and category, the rating score, the timestamp of the rating and review, and the average helpfulness of the rating given by others (on a scale of 1-5).

The dataset, originating from several data sources, has been merged into a single CSV file named `The E-commerce Dataset.csv`.

## Tools and Libraries Used

This project was completed using Jupyter Notebook with Python. The main libraries used include:
- `pandas`
- `seaborn`
- `matplotlib`

## Project Tasks

The project was divided into four main tasks:

1. **Data Cleaning**: Removing missing data and displaying the DataFrame.
2. **Descriptive Statistics**: Providing data summarization and descriptive statistics.
3. **Plotting and Analysis**: Exploring the correlation between gender/helpfulness/category and ratings.
4. **Outlier Detection and Removal**: Defining and removing outlier users, reviews, and items.

## Findings

After analyzing the dataset, we found that:

1. **Gender and Ratings**: The male group tends to have a slightly higher number of ratings compared to the female group. However, the median rating (4.0) and the maximum rating (5.0) are the same for both groups. The mean rating score by females (3.72) is a bit higher than the mean rating by males (3.69).

2. **Helpfulness and Ratings**: There is a generally positive correlation between the average helpfulness of ratings and the actual ratings given by users. Higher average helpfulness levels tend to correspond with higher ratings received. However, there are fluctuations in the data, suggesting that other factors likely impact individual users' rating behaviors beyond just the average helpfulness assessment.

3. **Category and Ratings**: The majority of categories have a median rating of 4, with minimal variation observed within categories. However, there are notable disparities in the distribution of ratings among the categories of "Media," "Games," and "Books". The presence of outliers in the "Games" and "Books" categories suggests that there are some instances of extreme ratings for certain games or books.

4. **Brief Summary of Data**: The data contains information on 19,916 items, including key fields like rating, helpfulness, gender, and item categories. The ratings range from 1 to 5, with a mean of 3.7 out of 5 stars. The items span a wide price range, from \$12 to \$149, with an average price of \$82.19. There are 8,562 unique users, with 'Male' being the most common. The items belong to 9 distinct categories, with 'Movies' being the most popular. 'AOL (America Online)' is likely one of the most common items, potentially in the 'Online Stores & Services' category.

## Contributing

As this is an individual assignment, I am the main contributor. However, if you find any errors or areas of improvement, feel free to create an issue or submit a pull request.

## License

This project is part of a university assignment and the dataset was provided by the lecturer. Please use this for reference or educational purposes only.