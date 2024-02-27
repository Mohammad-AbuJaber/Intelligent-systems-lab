# CNN for Binary Classification: MNIST Dataset

## Goal
Experiment with Convolutional Neural Networks (CNNs) for binary classification using the MNIST dataset. The task involves predicting whether an input image depicts a digit greater than a threshold (τ), where τ is the average of all digits in the university ID.

## Dataset
Utilize the MNIST dataset, originally designed for multiclass classification on handwritten digits. In this task, the goal is binary classification based on the specified threshold.

## Model
Implement a 5-layer CNN with the following specifications:
- **Layer-1:** Convolutional layer with a 3x3 kernel and (X+4) output channels.
- **Layer-2:** Convolutional layer with a 3x3 kernel and (Y+15) output channels.
- **Layer-3:** Fully connected layer with ABC neurons.
- **Layer-4:** Fully connected layer with 16 neurons.
- **Layer-5:** Fully connected layer with 1 neuron.

Activation functions: ReLU for hidden layers, and sigmoid for the output layer. Each convolutional layer should be followed by an average pooling layer with a 2x2 window size and stride 2.

## Loss Function
Utilize binary cross-entropy loss (nn.BCELoss) for model training.

## Tasks
1. **Train Model:** Train the specified model on the GPU for 3 epochs using the Adam optimizer with a learning rate of 0.0005 and a batch size of 8.
2. **Plot Training Accuracy:** Visualize the training accuracy vs. epoch curve.
3. **Compute Testing Accuracy:** Evaluate the testing accuracy of the trained model.
4. **Plot Misclassified Images:** Display 4 misclassified images, showing the correct and predicted labels for each image.
