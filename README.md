It is an ANN concept model of predicting if a covid-19 infected patient will die or not based on their symptoms.

The database is collected from here: https://docs.google.com/spreadsheets/d/e/2PACX-1vQU0SIALScXx8VXDX7yKNKWWPKE1YjFlWc6VTEVSN45CklWWf-uWmprQIyLtoPDA18tX9cFDr-aQ9S6/pubhtml

There are countless missing values and invalid values in the dataset so i replaced those fields by random values as it is just a concept model. Adding random values to the dataset can add noise to the dataset. This model can perform better on an actual dataset.

I've used 3 hidden layers each layer contains 11 neurons.

Keras 2.0.4 was used to train the model so if you're facing KEYERROR 0 when opening the trained model use keras==2.0.4
