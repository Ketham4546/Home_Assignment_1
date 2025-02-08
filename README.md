# Home Assignment 1

## Student Information
- **Name:** Bharadwaj Ketham  
- **ID:** 700759639 
- **Course:** CS5720 Neural network and Deep learning, CRN23848

## Overview
This repository contains four deep learning assignments implemented using TensorFlow. The tasks include tensor manipulations, loss function comparisons, training models with different optimizers, and logging training progress using TensorBoard.

## Project Structure
- `1_tensor_manipulations.ipynb` - Tensor reshaping, transposing, and broadcasting operations.
- `2_loss_functions.ipynb` - Implementation of Mean Squared Error and Categorical Cross-Entropy losses.
- `3_mnist_optimizers.ipynb` - Training an MNIST model using Adam and SGD optimizers.
- `4_mnist_tensorboard.ipynb` - Training an MNIST model with TensorBoard logging.
- `README.md` - Documentation for all assignments.
- `requirements.txt` - List of dependencies required to run the project.

## Assignment 1: Tensor Manipulations & Reshaping
This task focuses on fundamental tensor operations such as reshaping, transposing, and broadcasting. The following steps were performed:
1. Created a random tensor with a predefined shape.
2. Determined its rank and shape using TensorFlow functions.
3. Reshaped the tensor into a new dimensional format.
4. Transposed the reshaped tensor to analyze its structure.
5. Created a smaller tensor and used broadcasting to align its dimensions with the larger tensor before performing element-wise addition.

### Key Concepts
- Tensor reshaping and transposition
- Broadcasting in TensorFlow

## Assignment 2: Implementing & Comparing Loss Functions
In this task, two different loss functions, Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE), were explored. The following steps were performed:
1. Defined true values and predicted values.
2. Computed the MSE and CCE loss values to compare their behaviors.
3. Slightly modified the predictions and observed how the loss values changed.
4. Plotted the loss values in a bar chart for visualization.

### Key Concepts
- Loss function behavior and sensitivity to prediction changes
- Visualization of loss function values

## Assignment 3: Training an MNIST Model with Different Optimizers
This task involved training the MNIST dataset using two different optimizers: Adam and SGD. The following steps were performed:
1. Loaded the MNIST dataset and performed preprocessing.
2. Built a simple neural network model with appropriate layers.
3. Trained one model using the Adam optimizer.
4. Trained another model using the SGD optimizer.
5. Recorded and compared training and validation accuracy trends.

### Key Concepts
- Effect of optimizers on model training
- Accuracy comparison of Adam vs. SGD

## Assignment 4: Training a Neural Network and Logging to TensorBoard
This task involved training an MNIST model while logging the training progress using TensorBoard. The following steps were performed:
1. Loaded and preprocessed the MNIST dataset.
2. Built a simple neural network model.
3. Configured TensorBoard logging and set up a directory to store logs.
4. Trained the model while logging accuracy and loss values.
5. Used TensorBoard to visualize trends in training and validation accuracy.

### Key Concepts
- TensorBoard logging for deep learning model training
- Analyzing loss and accuracy trends to detect overfitting

## TensorBoard Analysis
TensorBoard was used to monitor the training process and analyze loss and accuracy trends. The visualization helped in understanding:
- Patterns in training and validation accuracy curves.
- Signs of overfitting by comparing loss trends.
- The impact of increasing the number of training epochs on model performance.


## Dependencies
- TensorFlow  
- Matplotlib  
- NumPy  

## License
This project is for educational purposes only.
