# deep-learning-homework

## Which model has a lower loss?
Predictor for closing prices

## Which model tracks the actual values better over time?
Predictor for closing prices

## Which window size works best for the model?
A lower window size (eg window size = 1), sees the prediction follow the actual prices more closely. On the other hand, a larger window size (eg window size = 10), sees a smoother prediction.

Specifically with the predictor for closing prices, ;oss at window size of:
 * 10 is 0.0190;
 * 5 is 0.0187; and
 * 1 is 0.0104.

Therefore, a window of 1 works best for this model.
