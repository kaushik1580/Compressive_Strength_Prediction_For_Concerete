# Concerete_-Strength_Prediction

For any concrete building to withstand various stress application in daily life it needs to have high strength, and strength is shown in Compressive Strength terminology as concrete majorly is able to withstand compression. It is measured using Universal Testing Machine (UTM) where concrete cube (generally 28 days old) is made to take the load until it is failed. The cube is made of certain proportions of materials. With the age of the cube the strength also increases, almost 99% of the full strength is gained in 28 days.
It is very challenging to make a proper mix proportion for acquiring the required compressive strength, and there is no accurate method in designing the mix. Practically, mix design for special purpose is made by testing for so many random proportions until the desired value is obtained. 
I have developed a model to predict the concrete compressive strength from the quantity of the materials mixed to make concrete.
Here I used Support Vector Regression of different kernels with parameters using  SVR algorithm to understand, in what way the strength depends upon the considered attributes. Grid Search Optmization is used, in model to get best model along with better parameters. Dataset used for training the model contains more than 800 samples, with the attributes like age, cement, fly ash, water and other various materials used.  

### Conclusion:

Used RBF kernel as Grid Search gave the best parameter.

![1](https://user-images.githubusercontent.com/37845653/77755665-b89b3f80-7053-11ea-9d52-eb44c490dc5e.JPG)
![2](https://user-images.githubusercontent.com/37845653/77755657-b638e580-7053-11ea-8ede-92f7d7f62464.JPG)
![3](https://user-images.githubusercontent.com/37845653/77755661-b802a900-7053-11ea-96d3-bc003934ba38.JPG)

- Mean Absolute Error: 0.05868646431228403
- Mean Square Error: 0.0056405863418225125
