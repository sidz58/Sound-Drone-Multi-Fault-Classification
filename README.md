# Sound-Based Drone Fault Classification

### In this project, we will explore:
  1. How to process audio recordings for classification tasks.
  2. How to create a single model with a unified set of trained parameters for multiple classification tasks.


### We are focusing on three main tasks:
  1. Identifying the model of the drone.
  2. Determining the type and location of the fault, for example, 'left motor,' 'right propeller,' etc.
  3. Detecting the direction of movement.


#### Please find the attached dataset at this link:
The link leads to a public dataset uploaded on Kaggle:
https://www.kaggle.com/datasets/siddhz58/sound-based-drone-fault-classification


### Basic flow of the project:
  1. Accessing the dataset and extracting labels by parsing the file names.
  2. Converting the raw audio files to spectrograms for input into CNNs as image data.
  3. Normalizing the images and performing basic data preprocessing.
  4. Building a CNN model from scratch with multi-head outputs for the three tasks.
  5. Designing a custom loss function to evaluate and minimize the collective loss of the three tasks.
  6. Evaluating the trained model on test and validation data.


#### Further improvements:
  1. Using a pre-trained model for better performance.
  2. Performing hyperparameter optimization to find the optimal CNN architecture, learning rate, and training steps.
