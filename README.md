# Linear-regression-project
In this project linear regression model is fit to the Ecommerce dataset with amount spent yearly being the target variable. 
Initialy visualisations have been done to get an idea of the feature dependence on one another.
Further feature selection has been done using F regression and mutual info regression and it was found that time spent on website has least relation with the target variable.
Polynomial transformation of degree2 was also done on the orignal dataset.
Three datasets were evenntually formed for training. First being the orignal one ,second being the orignal dataset without the feature tie spent on website and third being the polynomial transformed orignal dataset
Linear regression model was fit on all the three and the model were used to predict on the test data
The scores of each were compared and it was found that the orignal dataset gave the best results,followed by the polynomial transformed one and lastly the one without time spent on website feature.
