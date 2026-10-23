# CS156 - Finding Patterns in Data with Machine Learning
Repository for code, pre-class workbook, assignments for my Minerva university course "CS156 - Finding Patterns in Data with Machine Learning"

## Structure
- `Class_Sessions` - concept explanations, derivations, experiments, visualizations, and reflections.
- other folders are for assignments (one folder/assignment)

## Current topics

### Session 1 — Introduction to Machine Learning
Students are introduced to different machine learning concepts in this class and we cover basic course expectations, class culture, and logistics.

### Session 2 — Linear and Logistic Regression
This class introduces the idea of tensors that describe physical properties and shows how they can be used with functions to perform classification and regression.

### Session 3 — Multivariate Linear Regression
This class introduces the concept of collinearity: what it means for vectors to "point" in the same direction. We'll explore how to detect this property with linear algebra and how it's used to make regression predictions. This is a code-focused lesson. We'll review the PCW for fitting a regression model to the Titantic data, and we'll introduce the concept of a rotation in a deep-dive python notebook.

### Session 4 — Decision Trees
The Session 4 notebook is stored at: `Class_Sessions`

### Session 5 — Naive Bayes
The purpose of this lesson is to introduce the Naive bayes model, and to provide a framework for students to generate their own explanations. It should reinforce the previous lessons by drawing connections between how partitioned vector spaces (Trees) relate to Bayesian probability, and how joint distributions can be compactly calculated with matrix multiplications (linear algebra)

### Session 6 — Logistic Regression and Maximum Likelihood Estimation
This session includes logistic-regression, Gaussian-MLE, Bernoulli likelihood, deriving the log-likelihood gradient, numerical MLE and probability threshold.

### Session 7 — Feed-Forward Neural Networks and Perceptrons
This class (and the next) introduce feed-forward neural networks. After class students will be able to draw basic neural network diagrams, write nested functions corresponding to FFNN processing, describe neural networks with matrices, and run the forward pass. While the next class focuses more substantially on back propagation and learning, this class introduces them as concepts.

### Session 8 — Gradients: Multivariate Derivatives
This class continues the work on neural networks by introducing the concept of gradients (a vector of partial derivatives) and the_ Jacobian _(a matrix of partial derivatives) and applying these concepts to backpropogation of errors in a neural network.

### Session 9 — Metrics and Cross-Validation
This session includes stratified 80/20 train/test splits, nonlinear SVMs on concentric-circle data compared with logistic regression, ROC curves, and ROC-AUC, grid search over SVM `gamma` and `C`, final evaluation on an untouched test set.

### Session 11 - Data Ethics and the Bias-Variance Trade off
This session includes discussion on bias, variance, the trade-off to find a balanced model, and ethics in ML.

### Session 12 - Basis Functions 1: Functions as Parameters
This lesson introduces a new trick for linear regression models: using basis functions as parameters. This allows linear regression models to fit non-linear data.

### Session 13 — Support Vector Classifiers and the Kernel Trick
This session includes discussion on column space, null space, SVCs (hard-margin, soft-margin, dual-decision cases with equations),  and data transformation into a new feature space using kernel trick (linear, homogenous quadratic, RBF).

## Notes: 
I have uploaded each `.ipynb` file directly from Colab for ease of user use-case. You can directly click `Open with Colab` and explore the code.
