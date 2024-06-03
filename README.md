# Handwritten Digit Recognition (Lenet5)

This project implements the Lenet5 architecture for recognizing handwritten digits. It utilizes the MNIST dataset for training and achieved an accuracy of 98.4%.

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/handwritten-digit-recognition.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd handwritten-digit-recognition
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook "hand written digit recognisation (Lenet5).ipynb"
    ```

## Features

- **Dataset**: MNIST dataset
- **Model**: Lenet5 architecture
- **Accuracy**: Achieved 98.4% accuracy in recognizing handwritten digits

## Model Architecture

The Lenet5 architecture consists of convolutional and pooling layers followed by fully connected layers. The final layer uses softmax activation for classification.

## Training

- The dataset is split into training, validation, and test sets.
- Data is normalized and encoded for training and evaluation.
- The model is compiled with categorical crossentropy loss and the Adam optimizer.
- Training is performed for 5 epochs with a batch size of 32.

## Evaluation

- The model is evaluated on the test set using accuracy as the metric.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- MNIST dataset provided by TensorFlow.
- Thanks to the contributors of TensorFlow and Keras for providing tools and resources for deep learning.

