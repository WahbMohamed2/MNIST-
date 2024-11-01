# Handwritten Digit Recognition using MNIST Dataset

## Project Overview
This project involves training a neural network model on the MNIST dataset, which consists of 70,000 images of handwritten digits (0-9). The model is designed to recognize and classify handwritten digits based on the training data.

## Model Architecture
The neural network consists of three layers:
- **Input Layer:** Receives the pixel values of the images.
- **Hidden Layer(s):** Processes the data and extracts features.
- **Output Layer:** Produces the probability of each digit (0-9).

After training, the model is saved for future use in testing and predictions.

## Test Data
A folder named **"digits"** is provided, containing PNG images of handwritten digits. This test data is used to evaluate the performance of the trained model.

## How It Works
1. **Training the Model:**
   - The model is trained using the MNIST dataset.
   - The training process involves adjusting the weights and biases in the neural network to minimize the prediction error.

2. **Saving the Model:**
   - Once the model is trained, it is saved to disk for later use.

3. **Testing the Model:**
   - The last cell of the code contains a while loop that iterates through the PNG files in the "digits" folder.
   - For each image, the model predicts the corresponding digit and outputs the predicted number.

## Usage
To use this project, follow these steps:
1. Ensure you have the required libraries installed (e.g., TensorFlow, Keras, NumPy).
2. Place your test images in the **"digits"** folder.
3. Run the code to train the model and test it on the provided images.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib (optional, for visualizations)

## Conclusion
This project demonstrates the application of neural networks in image classification tasks, specifically in recognizing handwritten digits using the MNIST dataset. The trained model can be used to make predictions on new handwritten digit images.
