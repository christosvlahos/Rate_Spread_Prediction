# Rate Spread Prediction
I was given this dataset for a data science interview as a take-home test. Its point was to perform some EDA and create a model that can predict
the rate spread for the loans in the dataset. Additionally they wanted me to extract the features that are most important for such a prediction.

This is a slighlty altered version of the notebook that I decided to upload here. It is not its final version, as I have already found a few things
I want to expand and explore more.

## Data
The data folder has two csv files, one with all the features (train_values.csv) and one with the target feature (train_labels.csv). Because all categorical
features are encoded, there is a description.txt file with explanation about every column.

## Notebook
In the notebook, I include a big part of exploratory data science, trying to get an understanding of the data and get some useful conclusions from that. 
I focus on some sections a bit more and then I deal with the missing values and outliers. Finally I build, train and test two models on updated data, 
a decision tree and a randoma forest regressor. Normally the rate spread would be a continous variable and a regression model would be enough. However
in this dataset the values are discrete (integers) so I am also using a confusion matrix metric to evaluate my models. 

## Libraries
All required packages are included in the requirements.txt file
