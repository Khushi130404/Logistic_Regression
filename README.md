# Logistic_Regression

This repository contains an implementation of logistic regression from scratch using foundational concepts such as step function, sigmoid function, and gradient descent. Additionally, it includes an implementation using sklearn for comparison. The project also includes visualizations and comparisons of these methods to provide a comprehensive understanding of logistic regression.

## Features

1. Step Function Implementation: Demonstrates the use of the step function for classification.

2. Sigmoid Function Implementation: Applies the sigmoid function for logistic regression, enabling probabilistic outputs.

3. Gradient Descent Optimization: Optimizes the logistic regression model using gradient descent.

4. sklearn Implementation: Uses the built-in LogisticRegression from sklearn for benchmarking and comparison.

5. Visualization: Includes visual plots to illustrate the behavior and performance of each implementation.

6. Comparison: Provides side-by-side comparisons of different methods to highlight their strengths and weaknesses.

## Dependencies

- numpy
- matplotlib
- pandas 
- scikit-learn

## Methodology

1. Step Function :
- A basic binary classification approach.
- Illustrates the limitations of hard classification boundaries.

2. Sigmoid Function :
- Smooth, probabilistic classification boundary.
- Output ranges between 0 and 1, allowing confidence levels for predictions.

3. Gradient Descent :
- Optimizes the logistic regression cost function by iteratively updating weights.
- Implements learning rate adjustments and convergence checks.

4. sklearn Implementation :
- Uses LogisticRegression from scikit-learn for a straightforward and efficient implementation.
- Provides a benchmark to compare the manual implementation's performance.

## Visualization
- Graphical representation of decision boundaries.
- Loss function convergence during gradient descent.
- Comparison of the performance of step, sigmoid, gradient descent, and sklearn implementations.
