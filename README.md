# Fin-Tech-Module-14
This module allow the exploration of Algorithmic trading

---

## Technologies

Python, Path, Pandas, sklearn.metrics, warnings

---

## Installation Guide

Create a dev environment.  Run module via Jupyter Lab. 

---

## Challenge asked and answered questions.
### Step 6: Use an Alternative ML Model and Evaluate Strategy Returns

Previous Period Results

                  precision    recall  f1-score   support 
            -1.0       0.00      0.00      0.00      1804
             1.0       0.56      1.00      0.72      2288

        accuracy                           0.56      4092
       macro avg       0.28      0.50      0.36      4092
    weighted avg       0.31      0.56      0.40      4092


Revised data Period Results

                  precision    recall  f1-score   support
            -1.0       0.46      0.39      0.42      1430
             1.0       0.58      0.64      0.61      1843

        accuracy                           0.53      3273
       macro avg       0.52      0.52      0.51      3273
    weighted avg       0.52      0.53      0.53      3273


### What impact resulted from increasing or decreasing the training window?
    
       Precision increased along with other figures such as accuracy overall.
       
short_window from 4 to 3
long_window from 100 to 75

                  precision    recall  f1-score   support
            -1.0       0.44      0.57      0.50      1438
             1.0       0.57      0.44      0.49      1852

        accuracy                           0.50      3290
       macro avg       0.50      0.50      0.50      3290
    weighted avg       0.51      0.50      0.50      3290


### What impact resulted from increasing or decreasing either or both of the SMA windows?
    
           As a result accuracy fell by 3 points but recall seems to be up by almost 20.  The comparision plot seems to be much closing between actual and strategy returns.
        
Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.

In conclusion, I chose the latter set of changes due to the cumulative end result being more in line with the sort of consistency and accuracy that we are looking for.  