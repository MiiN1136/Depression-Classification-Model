# Depression-Classification-Model

This repository contains beginner-friendly implementation and experiments on building, training, and evaluating a binary classification deep learning model using PyTorch and complementary ML tools. It covers the full workflow from data preprocessing to model design, training optimization, and performance evaluation.
<h2>Dataset</h2>
The dataset used is available on Kaggle under the name <b>Student Depression Dataset</b> and licensed under <b>Apache 2.0</b>. This is a real-world dataset originating from India.

<h2>Key features</h2>
<ul>
  <li>Data Preprocessing: Cleaned and transformed data, handled missing values, converted string ranges to numerical values, and managed complex data types like coordinate pairs.</li>
  
  <li>Data Splitting: Used train_test_split from scikit-learn for creating, training and testing the dataset.</li>

  <li>Model Architectures: Multi-layer perceptrons with nonlinear activations (ReLU).</li>

  <li>Training & Optimization: Used the <b>Adam</b> optimizer, with a weight_decay of 1e-4 to manage regularization and prevent overfitting.</li>

  <li>Evaluation Metrics: Computed accuracy, precision, recall and F1 score, and visualized the confusion matrix to analyze overall model performance using <b>confusion_matrix</b> and <b>ConfusionMatrixDisplay</b> from scikit-learn.</li>
</ul>

<h2>Model saving</h2>
Includes functionality to save the model and optimizer states mid-training to enable checkpointing.

<h2>Tools & libraries</h2>
<ul>
  <li>PyTorch, NumPy, Pandas, scikit-learn for modeling and data manipulation.</li>
  <li>Matplotlib for visualizing confusion matrices.</li>
</ul>
