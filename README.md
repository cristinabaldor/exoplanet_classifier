Using the public Kepler Exoplanet dataset, created a deep learning model to accurately classify exoplanet candidates based on relevant features.

I used two models, a sequential model and a grid search model. Both models use the same top five most important features and pre-processing. The sequential model takes 5 inputs and uses a neural net of two layers of 15 hidden nodes to three categorical outputs. After training, the model scored an 87% accuracy score.

The second model is a GridSearchCV model with a support vector machine linear classifier. After training it scored a 75% accuracy score.

The sequential model is a better fit for this type of data, and I believe accurate enough to predict new exoplanets. More data on which to train, and other more relevant features, perhaps some new features columns that are strongly correlated with other confirmed exoplanets, I think would improve its accuracy. I tried the model with a much deeper neural net (100 on 100 hidden nodes) and the accuracy was about the same.

Using Random Forest to select most relevant features

![image](https://user-images.githubusercontent.com/68877416/111363351-51acd700-8666-11eb-8c7d-639d0457bdca.png)

Neural net

![image](https://user-images.githubusercontent.com/68877416/111363467-77d27700-8666-11eb-9f60-9152f1b15ac7.png)

Testing accuracy for sequential
![image](https://user-images.githubusercontent.com/68877416/111363529-8c167400-8666-11eb-9b0e-2c38c3c18027.png)
