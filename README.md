# Bob Graham Round time prediction

Aims to predict the finishing time of someone attempted to complete a Bob Graham Round based on their previous race results. To use, enter the runner id (from the DUV site) for a runner you wish to choose to predict.

The code obtains a list of the current finishers via the Bob Graham API (http://bobgrahamclub.org.uk/api/data_bgr_listing.csv), along with their finishing time, and scrapes the DUV ultramarathon database (https://statistik.d-u-v.org/index.php) to obtain the race results for each of these finishers. A number of models are then trained on features for each runner with the target of predicting their BGR finish time. Models included are:

- Random Forest
- Polynomial Regression
- XGBoost
- SVR
- Neural Network

The RF model providided greater accuracy (RMSE) based on the current features.