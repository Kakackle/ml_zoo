# ML ZOO

A collection of Machine Learning projects, used for learning and exploration, on interesting topics, learning through fun

### Project 1. Predicting Walmart Sales

Predicting the weekly sales of 45 different Walmart Stores, based on data from 2010 - 2012.
The factors considered include:
* The average air temperature in the region
* The cost of fuel in the region
* That week's consumer price index
* The unemployment rate in the region
* Whether a holiday occured in that week
* (engineered) the month the week happened in
* (engineered) the week's number within the month

The main goal of this project is to predict the weekly sales of any of the Walmart stores considered, using regression models, but, an additional task could involve the prediction of the store based on the sales and other factors

See the notebook with project results and the development process described in depth in a nice, viewable format: [Notebook Viewer](https://kakackle.github.io/ml_zoo/predicting_walmart_sales.html)


### Project 2. Spotify data and more for song genre classification and song recommendations
#### Song recommendation
* Start with basic song data
* Test out multiple approaches - cosine similarity, KNN
* Try to incorporate lyrics data
* Try to incorporate more metadata
* Try to incorporate user playlist data / collaborative filtering / etc

#### Genre classification
* or key classification
* or song stat regression (as in how joyful is a song likely to be from an artist, in a key, with a bpm, from a year)

See the project results: [work in progress](https://kakackle.github.io/ml_zoo/song_recommender.html)


### Project 3. Stroke prediction - Classical ML
#### PT 1. Stroke prediction, matplotlib, seaborn
1. EDA with seaborn
2. cleaning if necessary
3. classification training:
    * naive bayes
    * support vectors with different kernels (not just linear)
    * dimensionality reduction / PCA and dimension visualization
    * other methods / model types
4. coefficients etc exploration?
5. 

See the project results: [work in progress](https://kakackle.github.io/ml_zoo/stroke_prediction.html)

### Project 4. Store sales with neural networks
#### Walmart sales from project 1
#### Rossmann sales prediction (6 weeks) on data of different nature
1. With TensorFlow on raw data (cleaned-up NaNs, errors, inconsistencies)
2. With TensorFlow WITH engineered features from project 1
3. With PyTorch?


### Project 5. Neural Network Classification - Binary on Stroke and Multiclass on obesity
Sources:
* Obesity : [kaggle competition](https://www.kaggle.com/competitions/playground-series-s4e2/overview) - using a synthetic (generated using a DL model trained on [real data](https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster)) dataset
* Stroke: [kaggle dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
#### Obsesity
Non-obvious attributes:
* FAVC - Frequent consumption of high caloric food
* FCVC - Frequency of consumption of vegetables
* NCP - Number of main meals
* CAEC - Consumption of food between meals
* CH20 - Consumption of water daily
* CALC - Consumption of alcohol
* SCC - Calories consumption monitoring
* FAF - Physical activity frequency
* TUE - Time using technology devices
* MTRANS - (method of) Transportation used
Obesity scores/classes (NObesity) are:
* Underweight Less than 18.5
* Normal 18.5 to 24.9
* Overweight 25.0 to 29.9
* Obesity I 30.0 to 34.9
* Obesity II 35.0 to 39.9
* Obesity III Higher than 40






### Project 4. SPAM or something classification

### Project 5. Sign Language Recognition

### Project 6. Determine if producs in photos are the same

### Project 7. Multi-objective recommender system for stores?

### Project 8. Rossman store sales (or other store) prediction with significantly different factors than project 1
