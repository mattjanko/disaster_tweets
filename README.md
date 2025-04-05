**Project synopsis.** In this project, we consider a collection of Tweets labeled according to whether they are about natural desasters. We are interested in developing a recurrent neural network able to identify novel Tweets about natural disasters. We train a deep learning model with dropout layers and tune the model's dropout rate and learning rate.

Repository contents:

* disaster-tweets.ipynb - a Jupyter notebook with our EDA, preprocessing, model building, hyperparameter tuning, and discussion
* train.csv and test.csv - training data for our model and a holdout set for a Kaggle competition
* submission.csv - a flat file with classifications for the Kaggle competition
* leaderboard.png - a screenshot showing our model's F1 score as assessed on the holdout data
* PNGs with images depicting the training process, hyperparameter tuning, and classification performance on the holdout images
