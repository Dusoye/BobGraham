# Bob Graham Round Prediction

Aims to predict the finishing time of someone attempted to complete a Bob Graham Round based on their previous race results. 

The code obtains a list of the current finishers, along with their finishing time, and scrapes the DUV ultramarathon database to obtain the race results for each of these finishers. A random forest model is then trained on features for each runner with the target of predicting their BGR finish time.

To use, enter the runner id (from the DUV site) for a runner you wish to choose to predict