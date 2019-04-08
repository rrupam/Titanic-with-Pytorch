# Titanic-with-Pytorch
Using Pytorch to solve the famous titanic dataset problem, or in other words, killing a fly with a tank. 

The problem is on the ill fated ship Titanic, which sunk in the Atlantic ocean in 1912, killing many passengers on board. We are given the data related to each passenger like age, sex, ticket price, cabin class etc and the problem is to build a model that predicts correctly whether a particular passenger survived or not. 

This is a popular problem Kaggle competition problem and has been solved to no end. Noetheless, it served as a useful baby project to explore the Pytorch library, which I had just learned. 

First, I prep and clean up the data - like filling in missing values and discarding some parameters which I don't think are important. 
Next, I use a neural network with two fully connected layers and a hidden middle layer. 

The final results are evaluated on the Kaggle website. The topmost score I got was 0.7703, which placed me in the 5000-6000 category. I did not use any sophisticated machine learning algorithm like random forests, which I think could produce better results. I reierate that this project was to learn to use Pytorch. 
