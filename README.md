# Starbucks Capstone Project | Udacity - ML Engineer Nanodegree

## Overview

Starbucks, one of the world’s most popular coffee shops, frequently offers promotions through its rewards app to boost sales. These promotions range from simple advertisements to discounts and BOGO (buy one get one free) deals. This project aims to tailor these offers based on customer responses to previous promotions and predict future responses. First, Exploratory Data Analysis (EDA) is performed to understand the data's characteristics. Then, machine learning models are developed to predict customer responses, enabling Starbucks to better target their offers.

## Datasets and Inputs

For this project, the data sets are provided by Starbucks and Udacity in the form of three JSON files. These contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.
-   portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
-   profile.json - demographic data for each customer
-   transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**

-   id (string) - offer id
-   offer_type (string) - type of offer ie BOGO, discount, informational
-   difficulty (int) - minimum required spend to complete an offer
-   reward (int) - reward given for completing an offer
-   duration (int) - time for offer to be open, in days
-   channels (list of strings)

**profile.json**

-   age (int) - age of the customer
-   became_member_on (int) - date when customer created an app account
-   gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
-   id (str) - customer id
-   income (float) - customer's income

**transcript.json**

-   event (str) - record description (ie transaction, offer received, offer viewed, etc.)
-   person (str) - customer id
-   time (int) - time in hours since start of test. The data begins at time t=0
-   value - (dict of strings) - either an offer id or transaction amount depending on the record

## Files
The following files attached to this GitHub's repository include the following:
-   **[Starbucks_Capstone_notebook.ipynb](https://github.com/luongnguyentrong/starbuck-udacity-capstone/blob/master/Starbucks_Capstone_notebook.ipynb)**: This is the Jupyter Notebook in which I performed all my work.
-   **[data](https://github.com/luongnguyentrong/starbuck-udacity-capstone/tree/master/data)**: This contains the three JSON files provided by Starbucks / Udacity as noted above.

## Acknowledgements
Special thanks to Starbucks and Udacity for providing the data utilized in this project!