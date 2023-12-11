# Alzheimer Detection from MRI Images using CNN

This code is designed to perform Alzheimer's disease detection using a Sequential Convolutional Neural Network (CNN). The dataset includes images categorized into four classes: 'MildDemented', 'ModerateDemented', 'NonDemented', and 'VeryMildDemented'. The code demonstrates loading and preprocessing the data, creating a Sequential CNN architecture, training the model, and evaluating its performance.


The dataset used for the project is [here](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images)
## Prerequisites
- Python 3.x
- Jupyter Notebook or Colab environment
- Libraries: opendatasets, pandas, numpy, scikit-learn, matplotlib, cv2, keras

## Instructions
1. Open the provided Jupyter Notebook (Alzheimer_detection.ipynb) in your preferred environment.
2. Make sure to install the required libraries using `!pip install opendatasets`.
3. Run the notebook cells sequentially to perform the following tasks:
    - Download the dataset from Kaggle using opendatasets.
    - Load and preprocess the Alzheimer's dataset.
    - Create a Sequential CNN architecture for Alzheimer's detection.
        - The Sequential Model consists of convolutional layers (Conv2D) with ReLU activation, max-pooling layers, batch normalization, depthwise convolutional layers, and global average pooling. Dropout is applied for regularization.
        - The final fully connected layer produces an output with softmax activation for multi-class classification.
    - Train the model on the dataset and evaluate its performance.
4. Review the generated visualizations, model summary, and performance metrics.

## Note
- Ensure that you have the necessary permissions and API keys to download datasets from Kaggle.
- Adjust hyperparameters, model architecture, or other configurations as needed.

Feel free to customize the code for further experimentation or improvement.
