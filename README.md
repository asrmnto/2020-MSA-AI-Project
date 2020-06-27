#  :chart_with_upwards_trend: Microsoft Student Accelerator 2020 - AI and Advanced Analytics Project

This project uses a [dataset](https://www.kaggle.com/datasnaek/youtube-new) which includes data on daily trending Youtube videos. 
The main objective was to create a machine learning model that could accurately predict how many 'views' a Youtube video will get based on features such as its' channel, publish date, category, and likes/dislikes/comment counts. This can also be simply modified to predict other variables such as the number of views, dislikes or comments a video will get instead. A model similar to this can be utilised in the marketing and advertising fields to answer queries such as "What is the best time to upload a video?".


Since labeled data is available, this is an example of a supervised learning problem. Specifically, a linear regression algorithm known as Decision Tree Regressor was employed to predict the number of views of the testing set. This was based on a 5-fold cross validation that was performed which showed that it was the best performing algorithm out of other regressors such as Linear Regression and Elastic Net Regression. 


The result was an R^2 score of 0.95 which is very close to a perfect score of 1, deems the model to be perform fairly well and can potentially be used for further modelling.

## Environment Setup and Dependencies

The project was created using Jupyer Notebooks.

The following libraries and their versions are given as below:
- Python = 3.6
- Pandas = 1.03
- SciPy = 1.41
- Scikit-learn = 0.22.1

## Running the Model

1. Open the "msa_ai.ipynb" file in Azure/Jupyter Notebooks.
2. Under the "Kernel" dropdown, select "Restart & Run All".
3. The model should now be trained using given model.

Comments have been provided in the notebook which explains the steps of the model.
