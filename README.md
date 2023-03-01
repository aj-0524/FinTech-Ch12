![An image for the header of the Repository](banner.png)

# *Credit Risk Regression Analysis*

The purpose of the analysis was to determine the creditworthiness of people applying for loans using two linear regression models. One using the original data from the 'lending_data.csv' file and another with the resampled data. 

---

## **Required Technologies**

This application requires `python 3.7.13` along with the following libraries, `pandas`, `numpy`, `scikit-learn`, and `imbalanced-learn`.

---

## Installation Guide

You can install the pandas, numpy, scikit-learn, and imbalanced-learn libraries to your device by running the following prompts in your command line interface (CLI).

```pip install pandas```

```conda install numpy```

```conda install -U scikit-learn```

```conda install -c conda-forge imbalanced-learn```

---

## Usage

You can initiate the application in your Command-Line-Interface (CLI) by navigating to the site and running the file.

---

## Overview of the Analysis

The financial information that the data was on included the customers personal and loan data. For example; loan size, interest rate, and borrower income.

## Results

* Machine Learning Model 1:

```              pre       rec       spe        f1       geo       iba       sup

          0       1.00      0.99      0.91      1.00      0.95      0.91     18765
          1       0.85      0.91      0.99      0.88      0.95      0.90       619

avg / total       0.99      0.99      0.91      0.99      0.95      0.91     19384
```

The accuracy for the first model was 95%.


* Machine Learning Model 2:

```                   pre       rec       spe        f1       geo       iba       sup

          0       1.00      0.99      0.99      1.00      0.99      0.99     18765
          1       0.84      0.99      0.99      0.91      0.99      0.99       619

avg / total       0.99      0.99      0.99      0.99      0.99      0.99     19384
```

The accuracy for the first model was 99%.

## Summary

The model that seems to perform best is the second one. We know this because it has an accuracy score of 99%, as opposed to the first model's accuracy score of 95%. 

Performance does depend on the problems we are trying to solve due to the fact that we are trying to identify high-risk loans, which is why it is important to predict the 1's.

I would not recommend the first model as much as the second due to it's performance accuracy. The second model performs much better in regards to accuracy.

---

## Contributors

Adam Jimenez - FinTech Student

---

## License

2022 edX Bootcamps

