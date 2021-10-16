# Gold Production Estimation
## Project description
This project is provided by [Zyfra](https://www.zyfra.com/), a IIoT company which develops efficient solutions for heavy industry such as mining.  
A client of Zyfra searches for ways to estimate the gold outcome from the raw ore as well as for ways how to optimize the production process by adjusting certain parameters.  
Therefore the company provides two datasets. One for each step of the production process.

## Content
Within this project the following steps have been carried out:

- Loading and analysing the data
- Extensive Data preprocessing
- Calculation of missing features and the target (Gold recovery)
- In-depth Exploratory Data Analysis
- Definition of own scoring function (sMAPE)
- Evaluation of multiple machine leraning models via cross validation
- Model building, training and evaluation via pipeline
- Hyperparameter tuning

## Outcome
- The final models have an combined sMAPE of 7.1, which is acceptable but has some potential to be further improved
-For further improvements the filling approaches could be changed, further features could be measured or more datapoints could be used.  
- The sMAPE for the first step in the production is much better that the one for the second one. Here some additional parameters in the second step could help to improve this issue
