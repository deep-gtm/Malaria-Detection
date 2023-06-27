# Malaria-Detection
A CNN model which predict whether a cell is parasitized with malaria or not.

## Things I Learned In This Project :-

### Basic
1. How to use tensorflow dataset (in this used malaria dataset)
2. Image resizing and rescaling using tf methods
3. Data processing.
4. Data Visualization using matplotlib and seaborn
5. How Convolution Neural Network Work

### Tensorflow APIs
1. Sequntioal API (tf.keras.Sequential)
2. Functional API
3. Model Subclassing (Using Model and Layer)
4.   Custom Model and Layers

### How to Measure Performance Of Classification Models
1. Precision = TP/(TP+FP)
2. Recall = TP/(TP+FN)
3. Accuracy = (TP+TN)/(TP+TN+FP+FN)
4. Confusion Matrix and How to visualize it using seaborn (heatmap)
5. ROC (receiver operating characterisitc) plot, for finding best threshold value

### Tensorflow Skills I learned :-
#### Callbacks
1. Tensorflow Callbacks (These are method which we can when model is training)
2. LearningRateScheduler (For chaing learning rate)
3. EarlyStop
4. Model Checkpointing (For saving model at best state we want)

#### Tensorboard
1. Logging Data
2. View Model Graphs
3. Hyperparameter Tuning
4. Profiling and Visualizations

#### Mitigating Overfitting and Underfitting

##### Underfitting
Underfitting occurs when a machine learning model fails to capture the underlying patterns and relationships in the data, resulting in poor performance. Here are some methods to mitigate underfitting:
1. Increase Model Complexity
2. Increase Traingin Data
3. Hyperparameter tunning
4. Profiling and Visualizations

##### Overfitting
Overfitting occurs when a machine learning model becomes too complex and starts to memorize the training data instead of generalizing well to unseen data. Here are some methods to mitigate overfitting:
1. Increase training data
2. Simplify the model
3. Regularization: Regularization techniques add a penalty term to the loss function during model training, discouraging the model from assigning excessive importance to individual features. L1 and L2 regularization (also known as Lasso and Ridge regularization) are commonly used regularization techniques that can help prevent overfitting.
4. Early stopping: During the training process, monitor the model's performance on a separate validation set. If the performance starts to deteriorate after reaching an optimal point, stop the training early to prevent the model from overfitting the training data.
5. Data augmentation: Data augmentation techniques can artificially increase the size of the training dataset by applying various transformations or perturbations to the existing data. This can help expose the model to a more diverse range of examples and reduce overfitting.
6. Dropout: Dropout is a regularization technique commonly used in neural networks. It randomly drops out a certain percentage of neurons during each training iteration, forcing the network to learn more robust and generalizable representations.
7. Hyperparameter tunning : Grid search ,Random search

### Data Augmentation
1. With tf.images and keras
2. Cutmix Augmentation
3. Mixup Augmentation

### MLOPs with wandb

