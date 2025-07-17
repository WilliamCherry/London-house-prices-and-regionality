# London-house-prices-and-regionality

- Project Goals

Build a regression model in order to predict house prices in London.

Quantify regional affordability disparities across the UK.

Present the findings using an interactive Tableau dashboard which can be viewed here: https://public.tableau.com/app/profile/will.cherry/viz/PropertyPricesinLondonRegionalAffordability/PropertyPricesinLondonRegionalAffordability

- Techniques & Evaluation

Modeling Approach: Random Forest was selected as the primary method due to its robustness to noise and consistently strong performance across various regressors 

Feature Engineering & Tuning: Three model versions were evaluated:

- Base model with original features

- Hyper-parameter tuned model

- Tuned model + two extra predictors: (Borough-level average income & Monthly CPI)

The third model delivered the best accuracy.

Evaluation Metrics:

R² to assess variance explained by the model

RMSE to measure average prediction error

Technical Challenges:

- Learning and applying GeoPandas for geospatial feature integration

- Identifying optimal variable combinations during hyperparameter tuning
