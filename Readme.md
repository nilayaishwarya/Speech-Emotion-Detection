Notebook provides a simple way of emotion detection from voice.
The sample voice data used is from raavdess data.
The notebook utlizes following frameworks:
librosa: detecting features from sound
soundfile: load data from sound file (.wav)
sklearn: 
    model utilizes MLPClassifier.
    This is a Multi-layer Perceptron Classifier; it optimizes the log-loss function using LBFGS or stochastic gradient descent. Unlike SVM or Naive Bayes, the MLPClassifier has an internal neural network for the purpose of classification. This is a feedforward ANN model.
