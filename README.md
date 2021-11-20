# Flight_Price_Prediction
## Description
A machine learning web app that predicts the price of the flight based on several features. The model is built using Random forest regressor with a R2 score of 81.38% after going through Hyper Parameter tuning(RandomizedSearchCV).
The web application was developed using flask framework and deployed using heroku and the link for the application is https://flight-prices-prediction-app.herokuapp.com/

## How to use the application
<ul>
<li>The user has to enter the various parameters asked in form like arrival date,departure date,source ,destination,stopage and airline name.</li>
<li>Then press the submit button</li>
<li>After which the machine learning model at the backend will predict the price of flight.</li>
</ul>

## Methodology
<ul>
<li>The dataset used for training the model is  https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh.</li>
<li>Used a 50-layer deep learning model, RESNET-50, to extract features from the image</li>
<li>Used Word embeddings to convert words to vectors</li>
<li>Language Modeling: used Recurrent Neural Network and LSTM to generate caption.</li>
</ul>

### Flowchart of Methodology
![](Flowchart_of_Methodology.JPG)

## I/O screenshots
### Input
![](/Screenshots/Input.png)
### Output
![](/Screenshots/Output.png)

## Authors
Ayush Goel

## License
[MIT](https://choosealicense.com/licenses/mit/)
