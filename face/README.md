The dattabase used is the extended Yale Database B

Contains three different models:
1. Using PCA and forming an average vector for each person. Uses less space but the accuracy is around 70%.
2. Using PCA and forming a vector for each image. Increases the accuracy to around 80-85% but inncreases the memory cost too.
3. This extends the second model and uses a neural network for prediction. So, PCA is used to reduce the size of input vector and rest work is done by the Neural Net. Using a Neural Net boosted the accuracy to 98%!!!( with a little cost of memory and computation)

The code for the Neural Net is taken from [this repo](https://github.com/vtshitoyan/simpleNN).
