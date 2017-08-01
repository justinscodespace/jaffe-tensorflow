# jaffe-tensorflow
Crude CNN using tensorflow for facial emotion recognition on the JAFFE dataset.

The code includes no modifications for image preprocessing on the JAFFE dataset (available freely <a href='http://www.kasrl.org/jaffe.html'>here</a>). It utilises a simple CNN model using tensorflow to predict facial emotions, which have been labelled by hand.

### About the CNN
The CNN includes 4 sparsely connected convolutional layers and 2 densely connected softmax and relu output layers for prediction. It also includes dropout to avoid overfitting data and mini batch learning.
