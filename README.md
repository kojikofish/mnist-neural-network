# MNIST Handwritten Digit Classifier

This is my first neural network project. I used TensorFlow and the MNIST dataset to train a model that recognizes handwritten digits from 0 to 9.

## Model

The model has:

- A Flatten layer for changing each 28 × 28 image into 784 pixel values
- Two hidden layers with 128 neurons and ReLU
- An output layer with 10 probabilities for digits 0–9

## Results

The model was trained for 5 epochs.

- Test accuracy: 97.85%
- Correct predictions: 9,785
- Incorrect predictions: 215

I also looked at examples of correct and incorrect predictions and made graphs showing the model's accuracy and loss during training.

## File

- `mnist_digit_classifier.ipynb` contains the code, explanations, graphs, and results.

## References

- [GeeksforGeeks handwritten digit tutorial](https://www.geeksforgeeks.org/python/python-classifying-handwritten-digits-with-tensorflow/)
- [3Blue1Brown: But what is a neural network?](https://www.youtube.com/watch?v=aircAruvnKk)
