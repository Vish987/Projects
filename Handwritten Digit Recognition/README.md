# Handwritten Digit Recognition

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The model is trained using TensorFlow and Keras, and a Pygame interface is provided to draw digits and see the model's predictions in real-time.

## Features

- Handwritten digit recognition using a trained CNN model
- Interactive drawing interface to input digits and classify them in real-time
- Simple and intuitive GUI using Pygame

## Files

- `handwriting.py`: Script to train the CNN model using the MNIST dataset and save the trained model
- `recognition.py`: Script to load the trained model and provide a Pygame interface for digit recognition

## How to Use

### Setup

1. **Clone this repository to your local machine:**
    ```bash
    git clone https://github.com/Vish987/Projects.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Projects/'Handwritten Digit Recognition'
    ```

3. **Install the required packages:**
    ```bash
    pip install tensorflow pygame numpy
    ```

### Training the Model

1. **Run the `handwriting.py` script to train the model:**
    ```bash
    python handwriting.py model.h5
    ```
    - This will train the CNN model on the MNIST dataset and save the trained model to `model.h5`

### Running the Recognition Interface

1. **Run the `recognition.py` script to start the Pygame interface:**
    ```bash
    python recognition.py model.h5
    ```
    - Ensure that `model.h5` is in the same directory as `recognition.py`

2. **Use the Pygame interface:**
    - **Draw a digit:** Click and drag to draw a digit on the grid
    - **Reset:** Click the "Reset" button to clear the grid
    - **Classify:** Click the "Classify" button to classify the drawn digit using the trained model

## Example

When you train the model, you'll see the current epoch and its progress along with the model's current loss and accuracy.

```plaintext
Epoch 1/10
1875/1875 [==============================] - 22s 11ms/step - loss: 0.2366 - accuracy: 0.9280
...
Epoch 10/10
1875/1875 [==============================] - 19s 10ms/step - loss: 0.0280 - accuracy: 0.9906
313/313 - 1s - loss: 0.0381 - accuracy: 0.9877 - 1s/epoch - 4ms/step
...
```

When you run the recognition interface, you'll see a window with a grid where you can draw any digit. Once you click "Classify," the model will predict the digit and display the result. Once you click "Reset," the grid is cleared to allow you to draw again.
