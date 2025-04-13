# Credit Score Classification with Machine Learning

## Overview

This project demonstrates how to classify customers based on their credit scores. Banks and credit card companies can use this classification to quickly assess a customer's creditworthiness, making it easier to issue loans to those who qualify. A customer with a good credit score is more likely to receive favorable loan terms from financial institutions.

This implementation is based on the article "[Credit Score Classification with Machine Learning using Python](https://thecleverprogrammer.com/2022/12/05/credit-score-classification-with-machine-learning/)" by The Clever Programmer, with some additional tweaks and improvements.

## Project Objectives

- **Data Preparation:**  
  Clean and preprocess data, including handling missing values, converting string-based numerical data to float or integer types, and encoding categorical features.
  
- **Feature Engineering:**  
  Extract and convert useful features (e.g., transforming "Credit_History_Age" from "X Years and Y Months" to decimal format).
  
- **Model Building:**  
  Utilize various Random forest algorithm to classify customers into different credit score categories.
  
- **Prediction:**  
  Take some features as input and predict whether or not the customer with that information is credit worthy or not.

## Features
- **Data Exploration:**  
  - Did a lot of boxplot visualizations to know the features to work with  
  
- **Data Cleaning:**  
  - Conversion of mixed string numeric values to proper float/integer types.  
  - Handling missing values using appropriate imputation methods (median, mode, etc.).
  
- **Feature Extraction:**  
  - Transformations such as converting "Credit_History_Age" into a single decimal value.
  
- **Model Training and Evaluation:**  
  - Training a random forest model credit score classification.

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - Other dependencies as required

## Credits

This project was implemented based on the tutorial from [The Clever Programmer](https://thecleverprogrammer.com/2022/12/05/credit-score-classification-with-machine-learning/). Many thanks for the inspiration and the solid foundation provided by the original work.

## Contributing

Contributions to improve this project are welcome. Feel free to fork the repository and make a pull request with your improvements.

## Questions or Feedback

If you have any questions, suggestions, or valuable feedback, please leave a comment or open an issue in this repository.

---

Feel free to adjust and expand on this README to match any additional features or nuances specific to your implementation. Happy coding!
