# Bharat-Intern
Here is a brief overview of the key aspects of the project:

**Activation Functions:**
I explored various activation functions including ReLU, Softmax, and LeakyReLU to identify the most suitable for the task.

**Optimizers:**
Tuned models using a range of optimizers such as Stochastic Gradient Descent, Gradient Descent, Adam, Adadelta, AdaMax, FTRL, SGD, RMSprop, and NAdam.

**Loss Functions:**
Experimented with both Sparse Categorical Entropy and Categorical Entropy as loss functions.

**Learning Rates:**
Varied learning rates, including 0.001, 0.01, and the default rate, to analyze their impact on model training.

**Regularization Techniques:**
Implemented L1 and L2 kernel regularizers to enhance model robustness.

**Normalization and Dropout:**
Ensured standardization by testing models with different numbers of Batch Normalization layers and Dropout layers.

**Weight Initialization:**
Utilized Glorot and He initialization methods for both weight initialization and updates.

Following extensive tuning, we identified the optimal configuration for the Fashion dataset:

**Best Case Study:**
- Architecture: 3 layers with {256, 128, 64} neurons.
- Optimizer: Adam.
- Learning Rate: Default.
- Regularizers: L2.
- Batch Normalization: 2 layers.
- Dropout: None.

**Conclusion:**
Our rigorous hyperparameter tuning resulted in the optimization of the Fashion dataset, achieving the best validation accuracy, execution time, and memory parameters. Each validation accuracy represents an individual tuning test case, accounting for dataset constraints and specific requirements.

**Key Takeaway:**
Tailoring hyperparameters is a nuanced process that demands a deep understanding of dataset intricacies. As we continue our journey, we remain committed to refining our models for each unique challenge. 
