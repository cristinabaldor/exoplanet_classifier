# machine-learning-challenge

Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

I used two models, a sequential model and a grid search model. Both models use the same top five most important features and pre-processing. The sequential model takes 5 inputs and uses a neural net of two layers of 15 hidden nodes to three categorical outputs. After training, the model scored an 87% accuracy score.

The second model is a GridSearchCV model with a support vector machine linear classifier. After training it scored a 75% accuracy score.

The sequential model is a better fit for this type of data, and I believe accurate enough to predict new exoplanets. More data on which to train, and other more relevant features, perhaps some new features columns that are strongly correlated with other confirmed exoplanets, I think would improve its accuracy. I tried the model with a much deeper neural net (100 on 100 hidden nodes) and the accuracy was about the same.