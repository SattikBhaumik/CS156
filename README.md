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
The Session 4 notebook is stored at: `Class_Sessions/`

### Session 5 — Naive Bayes

- joint, marginal, and conditional probability,
- conditional independence,
- TF-IDF,
- Multinomial Naive Bayes,
- learned parameters,
- linear decision boundaries,
- confusion matrices,
- feature probabilities and Laplace smoothing.

### Session 6 — Logistic Regression and Maximum Likelihood Estimation

- Gaussian-MLE preclass review,
- logistic-regression parameters and Bernoulli likelihood,
- log-likelihood of synthetic *Mujhe Chahiye Bollywood* data,
- comparing proposed parameter values and deriving the log-likelihood gradient,
- optional numerical MLE and 95% probability threshold.

### Session 7 — Feed-Forward Neural Networks and Perceptrons

- MNIST MLP (784 → 128 → 64 → 10): matrix dimensions, training, validation, test metrics and confusion matrix,
- single-layer Sonar perceptron trained from scratch with stratified 3-fold cross-validation,
- Fashion-MNIST binary top-versus-trouser experiment with optional PCA and learning curves.

### Session 8 — Gradients: Multivariate Derivatives

- sigmoid derivatives and chain rule,
- manual scalar backpropagation through a computation graph,
- gradients of the dot product `w^T x`,
- vectorized backward passes,
- automatic differentiation with JAX,
- gradient-descent updates on model weights.

### Session 9 — Metrics and Cross-Validation

- stratified 80/20 train/test splits,
- logistic regression versus nonlinear SVMs on concentric-circle data,
- classifier probability surfaces,
- ROC curves, threshold tradeoffs, and ROC-AUC,
- train/validation/test separation,
- grid search over SVM `gamma` and `C`,
- final evaluation on an untouched test set.

### Session 13 — Support Vector Classifiers and the Kernel Trick

- nullspace, representer theorem, and SVC soft-margin/dual equations;
- linear, homogeneous quadratic, and RBF kernels and feature maps;
- linear and RBF SVC functions from the first PCW question;
- kernel comparisons on two-moons data;
- optional financial transaction classification (CSV not included);
- Yosemite Village NOAA 2011–2016 month prediction, with recorded CV/test results;
- supplementary SVR versus linear/RBF-feature regression.


## Notes: 
I have uploaded each .ipynb file directly from Colab for ease of user use-case. You can directly click "Open with Colab" and explore the code.
