# Random forest Refs:

## github links:

- https://github.com/johnberroa/RandomForest-StockPredictor
- https://github.com/Frid0l1n/Random-Forest

## Blogs and other sites 

- https://www.youtube.com/watch?v=RHeUqqrxP-w
- https://www.interactivebrokers.com/campus/ibkr-quant-news/random-forest-algorithm-in-trading-using-python/#:~:text=Random%20forest%20is%20a%20supervised,of%20overfitting%20in%20decision%20trees.


## random forest explanation:

- 1: set up the data source
- 2: clean the data (dropna())
- 3: create the model 
- 4: split the data into training and test data
- 5: once the data is split up, train the model on the Open, 'High', 'Low' and 'Volume'
- 6: the set the target to be close
- 7: once the model is trained, check the model score on a scale of 0-1, the higher the better. 
- 8: make a new prediction based on the trained model for the test data



# Long Short Term memory for stock market predictions refs: 

## githubs:
- https://github.com/ashendrasharma/Stock-Price-Prediction-Using-LSTM       

## Blogs and other sites:
- https://www.simplilearn.com/tutorials/machine-learning-tutorial/stock-price-prediction-using-machine-learning


## lstm explantion:

- this method takes two inputs
- tldr: take 4 days of data to try to predict the next days closing price
- repeat this process until the trainig is completed
- there are two ways to technically do lstm: 
    - numpy_tn
    - pytorch

