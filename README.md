# Neural_Network_Charity_Analysis
## Overview
In this module we explored the accuracy of neural networks. Given a set of data we were able to run models in order to see which model was the most accurate. 
## Results
When using machine learning or neural networks on data, one must first split the data into two sets: The target set and the features set. The features are data that determine the output of the target. In our charity loan set the column containing the information as to whether or not a previous loan was successful was used as the target set and all of the other factors were used to train a model to predictive with a certain accuracy if future loans with similar features would be successful. Here are the results:
### Data Preprocessing
- Whether a loan was successful was the target set
- Features in determining this were application type, affiliation, classification, use case, organization, income amount, and the asking amount. 
- Two variable were irrelevant and removed: identification number and name
### Compiling, Training, and Evaluation the Model
- The initial neural network model I used had 2 layers with 4 neurons in layer 1 and 8 in layer 2. 
- This initial NN didn't perform very well with an accuracy of only 50.9% with 50 epochs
![](https://github.com/ryanstaudhammer/Neural_Network_Charity_Analysis/blob/main/Resources/1stModel.png)
- The same model was run again with 100 epochs and much better results at 72.9% accuaracy
![](https://github.com/ryanstaudhammer/Neural_Network_Charity_Analysis/blob/main/Resources/2ndModel.png)
Next machine learning was evaluated to compare results. I tried to use three machine learning models: Logistic Regression, Random Forest Classifier, and Support Vector Machine but I had to ditch the SVM model because I couldn't get it to work, so instead I added another NN model with more neurons.
- The results from Logistic Regression and Random Forest models:
![](https://github.com/ryanstaudhammer/Neural_Network_Charity_Analysis/blob/main/Resources/MLModels.png)
- Logistic Regression fell short, but Random Forest didn't do so bad. The final NN model with more neurons performed the best:
![](https://github.com/ryanstaudhammer/Neural_Network_Charity_Analysis/blob/main/Resources/NNModel.png)
## Summary
It appears the Neural Network model performed best when enough epochs and neurons were added with an accuracy rating of  , still short of the goal, but the best performing model. 
