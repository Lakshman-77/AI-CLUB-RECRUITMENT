# AI-CLUB-RECRUITMENT
#KAGGLE DIGIT RECOGNIZER
Approach to the Code:-
This project implements a simple two-layer neural network from scratch to classify handwritten digits from the MNIST dataset. The key steps are:
1.	Data Preparation: The data is cleaned and normalized (scaled down) to make it easier for the model to work with. It’s then split into training and validation 
    sets. The labels are converted into a special format (one-hot encoding) that the model can understand.
2.	Model Design: The network has two layers—one hidden layer that uses ReLU (a function to handle non-linear patterns) and another layer that uses softmax to 
    predict the digits.
3.	Training the Model: The model learns by repeatedly making predictions, checking how wrong they are, and adjusting itself using backpropagation and gradient 
    descent to improve.
4.	Testing and Results: The model’s accuracy is checked on a separate validation set, and its predictions are visualized to see how well it’s doing.

This beginner-friendly implementation avoids external libraries for neural networks, emphasizing fundamental concepts.
