# Profit Optimization for Mail Campaign

## Project Overview
This project focuses on enhancing the profitability of a supermarket (the Client)'s credit card mail campaign. Previously, the client dispatched 10,000 unsegmented offers, resulting in 882 acceptances. By leveraging customer data, we aim to predict which customers are more likely to accept the offer, thereby optimizing the campaign's return on investment.

## Project Objectives
- Analyze customer purchasing behaviors to identify traits influencing credit card offer acceptance.
- Develop a predictive model to forecast customer responses to future campaigns.
- Implement a targeted mailing strategy to maximize profitability.


## Business Context
- **Cost per Mail**: $1.00
- **Revenue per Acceptance**: $12.50
- **Previous Campaign**: 10,000 mails sent, 882 acceptances, resulting in a profit of $1,275.
By predicting and targeting customers more likely to accept the offer, the model aims to increase profitability significantly.


## Data and the Analysis Process
We received 2 sets of data from **the client**. For one of the set, we will use it to create and fine-tuning the logistic regression model. For the other set, we will use it to predict the probability of customers accepting the mail campaign for the calculation of the profitability


## Results
- **Model Accuracy**: 80%
- **Predicted Acceptances**: 820 out of 10,000 targeted customers
- **Projected Profit**: $7,130
- **Profit Increase**: Approximately 596% compared to the previous campaign


## Project Structure
profit-optimization-for-mail-campaign/
├── Supermarket_Training.csv            # Dataset used for training the predictive model
├── Supermarket_Test.csv                # Dataset used for evaluating the model's performance
├── profit_optimization.ipynb           # Notebook containing data analysis, model development, and evaluation
└── README.md

