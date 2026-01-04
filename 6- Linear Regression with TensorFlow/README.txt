Linear Regression with TensorFlow

Overview
This project demonstrates how to train a neural network regression model to learn a simple mathematical equation:

y = 2*x1 + 3*x2 + 5

The goal is to understand how neural networks learn weights and bias when the data contains a clear structure.

What This Project Covers
- Regression using TensorFlow / Keras
- Mean Squared Error (MSE) loss
- Linear activation
- Training and evaluation
- Inspecting learned weights

Dataset
- Synthetic, clean data (no noise)
- Inputs: two features (x1, x2)
- Output: continuous value y
- Number of samples: 500
- Data generation formula:
  y = 2*x1 + 3*x2 + 5

Model Architecture
Input (2 features)
-> Dense layer (1 neuron, linear activation)
-> Output (y)

Expected Results
- Very low test loss (near zero)
- Learned weights close to [2.0, 3.0]
- Learned bias close to 5.0

Key Takeaway
Neural networks learn patterns only when they exist in the data.
With clean and structured data, even simple models perform extremely well.

Notes
This project is for learning and demonstration purposes.
