The dattabase used is the extended Yale Database B

Contains three different models:
1. Using PCA and forming an average vector for each person. Uses less space but the accuracy is around 70%.
2. Using PCA and forming a vector for each image. Increases the accuracy to around 80-855 but inncreases the memory cost too.
3. This extends the second model and uses a neural network for prediction. So, PCA is used to reduce the size of input vector and rest work is done by the Neural Net. 