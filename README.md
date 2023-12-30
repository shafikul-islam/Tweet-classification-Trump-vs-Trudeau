

# Tweet Classification: Trump vs. Trudeau

## Overview

This project delves into the realm of Natural Language Processing (NLP) by classifying tweets from two notable North American politicians: Donald Trump and Justin Trudeau. Using various machine learning models and vectorization techniques, the project aims to differentiate between the tweeting styles of the two politicians, offering insights into the unique linguistic patterns they exhibit.

![Donald Trump and Justin Trudeau](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/President_Donald_Trump_and_Prime_Minister_Justin_Trudeau_Joint_Press_Conference%2C_February_13%2C_2017.jpg/800px-President_Donald_Trump_and_Prime_Minister_Justin_Trudeau_Joint_Press_Conference%2C_February_13%2C_2017.jpg)

*Photo Credit: Executive Office of the President of the United States*

---

## Objectives

1. **Data Collection**: Utilize a corpus of tweets collected via the Twitter API.
2. **Data Preprocessing**: Transform and vectorize the tweets for machine learning.
3. **Modeling**: Train and evaluate classification models, including Multinomial Naive Bayes and LinearSVC.
4. **Analysis**: Investigate model performance and token importance.

---

## Tools & Libraries

- **Python**: Core programming language
- **scikit-learn**: For machine learning algorithms and metrics
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **matplotlib & seaborn**: Data visualization

---

## Key Findings

- The TF-IDF vectorization method outperforms the count-based approach.
- LinearSVC demonstrates superior classification accuracy compared to Multinomial Naive Bayes.
- Some confusion persists, particularly in classifying Trudeau's tweets as Trump's.

---

## Future Work

- Explore additional preprocessing techniques, such as removing URLs or specific stop words.
- Employ GridSearchCV for hyperparameter tuning.
- Integrate more recent tweets for enhanced model training.

---

## Contributing

Feel free to fork the repository, experiment with the code, and contribute to the project's development.

---

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

---

This `readme.md` provides a concise overview of your project, making it easier for others to understand and potentially contribute to your work.
