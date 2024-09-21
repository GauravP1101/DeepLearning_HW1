This repository contains the source code for Assignment 1, which is divided into three distinct sections. Each part has been implemented in a separate Jupyter Notebook, accessible via the links provided below.

The three parts of HW1 are as follows:

1.1) **Deep vs Shallow:**

   a) Function Simulation: Simulated two functions: 1) sin(5πx)/(5πx) and 2) sgn(sin(5πx)). The outputs were visualized, showing both model losses and predictions.
   
   b) Training on an Actual Task: Used the MNIST dataset to train CNN models with varying layer structures but a similar number of parameters. Loss and accuracy for each CNN model were visualized.

1.2) **Optimization:**

  a) Visualization of the Optimization Process: Created a deep neural network (DNN) with a single dense layer containing 418,060 parameters, repeating the training process eight times for consistent results.
   
  b) Observation of Gradient Norm During Training: Trained a DNN with a single dense layer consisting of 1,501 parameters, visualizing the gradient norm, which tracks the rate of change in loss relative to the model's parameters.
   
  c) What Happens When the Gradient is Near Zero?: A DNN was trained to observe the behavior as the gradient approached zero and compute the minimum ratio. After 100 epochs, it was noted that the loss did not reach zero.

1.3) **Generalization:**

  a) Can the Network Fit Random Labels?: Trained a DNN using the MNIST dataset, but with randomly assigned labels, to test the network’s ability to fit the data.
   
  b) Number of Parameters vs Generalization: Built ten CNN models with similar architectures but varying dense layer sizes, ranging from 39,760 to 15,90010 features, to explore the relationship between parameter count and generalization.
   
  c) Flatness vs Generalization: 
      	i) Developed two DNN models with identical architectures but different batch sizes (64 and 1000) and trained them on the MNIST dataset.
      	ii) Trained five DNN models with different batch sizes (10, 385, 760, 1135, and 1510) using the MNIST dataset to explore how batch size affects generalization.
	  
Required Python Packages:
- PyTorch
- pandas
- numpy
- sklearn (used only for PCA)
- matplotlib

Executing the codes:
Open the relevant .ipynb file for each part of the assignment. Running the Tests To run the tests, simply execute the cells in the .ipynb file. The code will automatically download the MNIST dataset and train the neural network models.
