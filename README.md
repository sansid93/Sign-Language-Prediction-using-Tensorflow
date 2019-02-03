# Sign-Language-Prediction-using-Tensorflow

Developed a Multi layer perceptron using TensorFlow to accurately classify the Sign languages using SIGNS dataset with 72% accuracy. 
RELU was used as an activation function for the hidden layers and Softmax function was used for the output layer

The below are the parameters that are used in training the neural network,

* X_train -- training set, of shape (input size = 12288, number of training examples = 1080)
* Y_train -- test set, of shape (output size = 6, number of training examples = 1080)
* X_test -- training set, of shape (input size = 12288, number of training examples = 120)
* Y_test -- test set, of shape (output size = 6, number of test examples = 120)
* Optimization algorithm: Adams
* No of Hidden layers:2
* No of Epochs: 1500
* learning_rate = 0.0001
* Mini_batch_size = 32
