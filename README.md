MNIST Digit Classification with Random Forest
A Comprehensive Guide to the Jupyter Notebook Implementation


📌 Overview
This Jupyter Notebook provides an end-to-end workflow for classifying handwritten digits from the MNIST dataset using a Random Forest (RF) classifier. Key features include:

Exploratory Data Analysis (EDA): Visualize digit distributions and sample images.

Model Training: Optimized RF classifier achieving ~97% accuracy.

Evaluation: Confusion matrix, precision/recall metrics, and feature importance.

Interactive Testing: User-friendly interface to test custom digit predictions.

📂 Notebook Structure
1. Introduction
Objective: Build a high-accuracy digit classifier without deep learning.

Dataset: MNIST (70,000 grayscale images of digits 0-9).

Why Random Forest?

Robust to noise and overfitting.

Computationally efficient for medium-sized datasets.

2. Data Loading & Preprocessing
Data Source: sklearn.datasets.fetch_openml.

Normalization: Scale pixel values to [0, 1].

Train-Test Split: 60,000 training samples, 10,000 test samples.

Visualization: Plot 10 sample digits with labels.


3. Model Training
Algorithm: RandomForestClassifier from scikit-learn

Hyperparameters:

n_estimators=100: Number of decision trees.
random_state=42: Reproducibility.

Training Time: ~5-10 minutes on standard CPUs.

4. Model Evaluation
Metrics
Accuracy: ~97% on test data.



🛠️ Usage Instructions
Run the Notebook:

Execute cells sequentially in Jupyter.

Ensure dependencies (numpy, matplotlib, scikit-learn) are installed.

Test Custom Images:

Use the interactive cell to input any test index (0-9,999).

Export Results:

Save confusion matrix/feature plots with plt.savefig().


📜 License
MIT © 2025 AKASH 

✨ Get Started
Open the notebook, run the cells, and explore how Random Forests interpret handwritten digits!

