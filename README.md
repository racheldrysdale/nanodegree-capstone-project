# Data Science Nanodegree Capstone Project 

## Project Motivation
My chosen case study was Sentiment Analysis on Tweets, in other words, processing natural language data to understand the writer's feelings or emotions.

## Data
The data file is very large and I could not upload it to this repository.  It is readily downloadable from the Kaggle website here: [Tweets Data](https://www.kaggle.com/kazanova/sentiment140).<br/>
The data is 1.6 million Tweets obtained from Twitter in 2009.  The Tweets are split evenly with 800k Tweets of Positive sentiment and 800k Tweets of Negative sentiment.  The data gives each Tweet an identifier, as well as giving the date (in the PDT timezone), the user who wrote the Tweet, and the text of the Tweet itself.

## File Descriptions
There is a single Jupyter notebook provided.  The notebook imports and cleans the dataset, pre-processes the data, builds a machine learning model, and uses GridSearchCV to choose the best set of hyper-parameters for the model.  Insights are drawns from the pre-processed data as well as the output of the model.

## Results
The results of the analysis can be found at my [Medium blog post](https://medium.com/@racheldrysdale_/can-we-understand-sentiment-from-just-140-characters-fd92827f43c7).

## Installation
There following libraries were used:
- pandas
- numpy
- sqlalchemy
- nltk
- re
- sklearn
- pickle
- matplotlib
- seaborn
- wordcloud

## Licensing, Authors, and Acknowledgements
I thank [Marios Michailidis](https://www.kaggle.com/kazanova) on Kaggle for providing the dataset. The image header in the blog post is from [@tengyart](https://unsplash.com/@tengyart) on Unsplash.  I relied on the library documentation to help with my project, particularly that of scikit-learn and nltk.  I also utilised StackOverflow when I ran into issues with my code.  There were two other articules I found particularly helpful in understanding model evaluation:
- [How to get feature importances from any sklearn pipeline](https://towardsdatascience.com/how-to-get-feature-importances-from-any-sklearn-pipeline-167a19f1214)
- [ROC curves and precision and recall curves for classification in python](https://machinelearningmastery.com/roc-curves-and-precision-recall-curves-for-classification-in-python/)
