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

