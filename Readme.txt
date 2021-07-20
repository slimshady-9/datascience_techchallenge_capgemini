Problem:
Develop product recommendation engine and detect bias based on data "electronics" and "modcloth"


In Solution.ipnyb :

1.Install the required packages like Surprise, Numpy, Pandas, Matplotlib, etc

2.Import the data and convert the csv into dataframe.

3.Electronics Dataset:
    *Analyze the data based on its attributes like Popularity, Satisfaction, plot graphs for better understanding.
    *For Using Collabrative System for recommendation, use SVD Matrix Factorization and train the model.
    *Use Hybrid Recommendation for showing the best 5 recommendations for a particular product for a user.

4.ModCloth Dataset:
    *Analyze the data based on its attributes like Popularity, Satisfaction, plot graphs for better understandin
    *Model-Based Collaborative Filtering method using Surprise.
    *Applied multiple GridSearch on SVD with different n_factors and reg_all to get best parameters for our SVD's model performance.
    *Estimate and predict which Product the user would like.
  
Attached published paper 'Addressing Marketing Bias in Product Recommendations.pdf' which I found online on ArVix shows that there is Marketing Bias with Product Selction as well as Consumer Satisfaction on both the datasets.
