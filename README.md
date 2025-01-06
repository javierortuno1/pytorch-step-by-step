# pytorch-step-by-step

## Chapeter01.ipynb
- Basics of Pytorch implementing a Linear regression model
- Organizing the code into three distinct parts
* a) Data Preparation
* b) Model Configuration
* c) Model training

## Chapter02.ipynb
- Use of TensorData and DataLoaders for mini-batch gradient descent
- Helper functions based on higher-order functions (Functions able to remember params and return another function)
- Saving code snapshots to and from the disk
- Monitoring with TensorBoard by using SummaryWriter
- Saving/ checkpointing loading models
- Improvement of the basic pipeline
    * Data Preparation
    * Model Configuration
    * Model training
 
## Chapter2_1.ipynb
- Defining a class for setting a training pipeline pattern:
      * Infrastructure components (model, loss, optimizer)
      * Training workflow (train/validation steps)
      * Data management (loaders)
      * Monitoring (losses, TensorBoard)
      * Model persistence (checkpointing)
- Understanding the different parts structures and part of the class able to represent the pipeline
- Reimplementing training methods: _mini_batch() and train()

## Chapter03.ipynb
- Classification model
- Logits
- logits into probabilities
- BCELoss
- Classification Thresholds
- Separability of classes and how it's related to dimensionality
- Metrics And Comparing models

## Chapter04.ipynb
- Binary Image classification model from a custom dataset
- Data Preparation for images, including normalization (scaling the values into a range)
- Function for allowing Custom datasets to be transformed
- Transform Pipelines
- Splitting the data based on the dataset indices
- Samplers (How to pick data from the dataset), including weighted samplers for imbalanced datasets
- Data Augmentation
- Visualizing the weights of hidden layers as sheets that must be multiplied by the Image feature sheets. It can be seen as filters
- Understanding gradients based on the activation function:
     - Gradients tell how sensitive (Level of certainty) a layer is about a value based on its current weights
          - High confidence (Low sensitive) weights will be updated a little bit
          - Low confidence (high sensitive) weights need to be updated
- Activation functions and how do they influence a deep model when analyzing the losses

