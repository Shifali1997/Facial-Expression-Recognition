# Facial-Expression-Recognition
The dataset consists of two columns i.e 'pixels' and 'emotion'.
The 'emotion' column has seven emotions i.e anger, disgust, fear, happiness, sadness, surprise and neutral. In 'pixel'  column we have the pixel values in the form of string with values separated by space.

Here a simple CNN model is created from which we get train_accuracy more tha 75% after 50 epochs. The validation_accuracy also shows some improvement initially (little more than 60%) but after 20 epochs remains almost constant.
Then I used the model to detect my face emotion using the webcam(Facial_Expression_Recog.ipynb)

To imprive the accuracy of our model, we can perform optimization using keras.tuners.
After tuning our previous model with optimum parameters we oberve that our training accuracy incresed more than 90% after 25 epochs.The validation_accuracy has increased more than 70% in only 50 epochs.(Optimizing my model.ipynb)

Finally I deployed the model using Flask(Flask for fer.ipynb)

Note- All the coding has been done in google colab.
