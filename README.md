# Project_3
# Database construction and analysis with hypothesis testing
## Extract, Transform, and Load data into MySQL database to answer business questions with the certainty of hypothesis testing.

**Author**: Brian Lafferty

### Business Problem:

Extracting data regarding moive production, Transforming information into a useable form, Loading the data into a MySQL database for future use, and answering relevant business questions with statistical testing.

This project provided me an enormous amount of experience. First, EXTRACTING public data with API calls. TRANSFORMING the data for storage and LOADING the data into a MySQL database I created. As the project continued with answering relevant business questions with statical tests. Rejecting or failing to reject my hypothesises I was able to answer with certainty crticial business questions.

### Data
Tens of thousands of movies from IMDb and The Movie Database (TMDB) covering features like title, revenue, rating, budget, and many more. The data was extracted in csv or json files with API calls. 


## Methods
- Extract and filter raw data from IMDb and TMDB
- 
- Visualization of data to explore and find underlying trends
- Used Principal Component Analysis (PCA) to improve model performance
- Analyzed data using multiple machine learning models
- Tuned hyperparameters of top two models for improved performance

## Model
The machine learning model preformed the best for this project was XGBoost. This model preformed best with the data when compared with a linear regression, k neareset neighbors, and random forest models. After tuning hyperparameters of the XGBoost model, it produced an accuracy score of 0.9453 on the test data.

## Results

![sample image](fig3.png)

> Identified key features that proved to be the secret to predicting hazardous objects.

#### Plotly 3d chart highlightly target class within dataset
![sample image](fig4.png)

> Visualizing the key features in this way allows for a clear understanding of the relationship the model was able to find.

#### XGBoost Model Metrics

-   The XGBoost model had an accuracy score of .94539 on the dataset without the key features.
-   The model had 40 false negatives! The worst possible option.
-   The model had 24 false positives. Which avoids Earths destruction, but does cause world wide panic.
-   With hyperparameter tuning the model improved its accuracy score by .02987

## Recommendations:
- When protecting Earth there is no choice besides the Decision Tree Model. It was able to predict all hazardous NEOs.




## Limitations & Next Steps
This dataset did not pan out how I had envisioned. The project does highlight the importance of data analysis and understanding the features in each dataset. As I continue to add to my machine learning knowledge I will continue to review this dataset and see if there are additional strategies I can explore.


### For further information


For any additional questions, please contact me on [LinkedIn](https://www.linkedin.com/in/brian-lafferty). 
