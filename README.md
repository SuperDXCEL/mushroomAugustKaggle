# Mushroom Binary Classification

In this competition you must predict whether a mushroom is edible or poisonous using the tabular data
you are provided with.

My approaches have been:

  -FastAI TabularPandas to prep the tabular data and then fed into a sklearn RandomForestClassifier, I
   have gotten about a 0.52 on my best submission which is pretty bad since it is not any better than
   random guessing.
   
  -From-scratch neural network which accuracy ranges between 0.45 and 0.52
  
  -XGBoost Classifier has gotten me a 0.97 accuracy submission, took more care of the data before feeding it to the model (see latest commit for mushroomxgbm.ipynb)
  
