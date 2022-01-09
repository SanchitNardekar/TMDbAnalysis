# TMDbAnalysis
Analysis of the TMDb dataset from Kaggle. Project 1 of the Udacity Data Scientist Nanodegree. The article that accompanies this repo can be found [here](https://medium.com/@sanchitastronomy/can-we-predict-big-budget-movie-flops-1407b175fcb4)


### Intro

This repository consists of the TMDb dataset and a Jupyter Notebook containing the analysis of the dataset. It looks to answer a few questions:
  1. Which genre of movies is the most profitable?
  2. Is there a discernable difference between keywords associated with flops vs successes?
  3. Are box office successes rated higher?
  4. Is there a temporal component to flops vs successes? 
  5. Can we predict box office flops?

The TMDb dataset was chosen for this analysis as it provides a good volume and variety of data to showcase data engineering and feature engineering, as well as the potential to build a predictive model to predict movie flops. 

### Contents

This repo contains the Juptyer Notebook used to conduct the analysis as well as the TMDb dataset downloaded from Kaggle. The Kaggle dataset is split into 2 csv files, one fo credits of each film and another for details about the movie itself. There is also a csv of the Consumer Price Index per year and month to explore time dependencies over decades. This analysis is currently unused in the article.

### Prerequisites

Apart from the libraries in the Anaconda distribution, this reportsitory makes use of the WordCloud library to plot a simple word cloud. [Linked](https://www.datacamp.com/community/tutorials/wordcloud-python) is a good tutorial on how to install and use WordCloud library in your own analyses. To install the WordCloud library, use the below:

`$ pip install wordcloud` or `$ conda install -c conda-forge wordcloud`

### Usage

This repository is primarily to highlight skills learned in the Udacity Advanced Data Science Nanodegree. As such, you can clone this repo to investigate the Jupyter Notebook in greater detail. 

### Credits

Compiled list of web links used throughout this project can be found below:
[TMDb Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
[WordCloud](https://www.datacamp.com/community/tutorials/wordcloud-python)
[CPI usage article](https://towardsdatascience.com/adjusting-prices-for-inflation-in-pandas-daaaa782cd89)

End with a joke!
![Jokes Card](https://readme-jokes.vercel.app/api)
