# Hypothesis Testing: Light vs Dark Theme for Online Bookstore

## Background

An online bookstore is seeking to optimize its website design to improve user engagement and increase book purchases. The website currently offers two themes:

1. Light Theme
2. Dark Theme

The bookstore's data science team wants to conduct hypothesis tests to determine which theme leads to better user engagement and higher conversion rates for book purchases.

## Dataset

The collected data contains user interactions and engagement metrics for both themes, including:

- **Theme**: dark or light
- **Click Through Rate**: Proportion of users clicking on links/buttons
- **Conversion Rate**: Percentage of first-time visitors who sign up
- **Bounce Rate**: Percentage of single-page visits without further interaction
- **Scroll Depth**: How far users scroll through website pages
- **Age**: User's age
- **Location**: User's location
- **Session Duration**: Length of user's website session
- **Purchases**: Whether the user bought a book (Yes/No)
- **Added_to_Cart**: Whether the user added books to cart (Yes/No)

## Hypothesis Testing Task

Objective is to conduct hypothesis tests to:

1. Determine if there is a statistically significant difference between the Light and Dark themes in terms of:
   - User engagement metrics (Click Through Rate, Scroll Depth, Session Duration)
   - Purchase rates
   - Conversion rates
   - Bounce rates

2. For each metric, formulated null and alternative hypotheses. For example:
   - H0: There is no significant difference in the conversion rate between Light and Dark themes.
   - H1: There is a significant difference in the conversion rate between Light and Dark themes.

3. Choosen appropriate statistical tests based on the nature of the data and the hypotheses.

4. Conducted the tests and interpret the results, considering the p-values and significance levels.

5. Drawn conclusions about which theme performs better for each metric, if any significant differences are found.

- [Source Code] (./Light_vs_Dark_Theme_Hypothesis_Testing.ipynb)

- [Dataset] (./website_ab_test.csv)
