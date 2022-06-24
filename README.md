# Exploratory Analysis & Predicting Store Sales
### Background

This project was part of the final group project for "Programming for Data Analytics: R &amp; Machine Learning" as part of the MBA in Data Analytics program at Seattle Pacific University. The code involves data wrangling, exploratory analysis, model comparison, and recommendation based on findings.

Data is obtained from a [kaggle competition](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data). The dataset is small containing about 206MB of data in 6 separate csv files.

* ***The presented problem:***
The client would like to find a model that best predicts the unit sales for thousands of items sold at different Favorita stores.

* ***The goals:*** 
    As a more accurate forecasting for their grocery stores can decrease food waste, unnecessary spending, and improve customer satisfaction. 

### instructions

The R [code](https://github.com/Samantha-Britschgi/Predicting-Store-Sales/blob/7cab252a44ae093b5bffdc45261f07bd098f61d4/RProject.Rmd) was written inside of R Studio, but any IDE editor that uses R should work to run the code.
 
### Process

    1. Installing & Importing Libraries
    2. Data Wrangling 
    3. Exploratory Analysis
    3. Basic Model Analysis
    4. Model Building (Lasso & XGBoost)
 	5. Model Enhancement with ensemble 
    6. Model Analysis
    7. Recommendations & Next Steps
    
### Findings
The initial basic model prediction indicated an NNetar model may be best. 

<img src="https://github.com/Samantha-Britschgi/Predicting-Store-Sales/blob/de62b47e18c676a0e1e6fd1374567a7b87c02d9c/BasicModelsStoreSalesPrediction.png" width="500" height="300" />

The models that were built were a basic Lasso, basic XGBoost, and then these basic models had a ensemble methods applied. The ensemble versions of the models did the best with higher accuracy and higher area under the curve.

<img src="https://github.com/Samantha-Britschgi/Predicting-Store-Sales/blob/de62b47e18c676a0e1e6fd1374567a7b87c02d9c/ModelsStoreSalesPrediction.png" width="550" height="300" />

Based on the accuracy being low (around 56%) for even the better performing ensemble method models, it is recommended that these ensemble models or NNetar model get expanded on to improve accuracy.

A [deck](https://docs.google.com/presentation/d/1xHHjIEd4K9kqAIH_BeZ8r5AlBUvGggd420_WfDpV8JQ/edit?usp=sharing) was made to easily display the process as well as present the findings in a comprehensible way.
