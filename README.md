# Leaf Identification CNN

A deep learning project for identifying leaf species using a Convolutional Neural Network (CNN). The model processes images of leaves and accurately classifies their species based on trained data.

## Features

- **Leaf Identification**: Detects and identifies leaf species from uploaded images.
- **High Accuracy**: Achieved through the use of CNN architecture optimized for image recognition.
- **Custom Dataset**: Trained on a curated dataset of leaf images.

## Technologies Used

- **Python**: Main programming language.
- **TensorFlow**: Deep learning framework for building and training the CNN model.
- **Keras**: High-level API for TensorFlow used for neural network development.
- **Matplotlib**: For visualizing training results and performance metrics.
- **NumPy**: For data manipulation and preprocessing.

## Installation and Setup

To run this project in Google Colab:

1. Open [Google Colab](https://colab.research.google.com/).
2. Clone the repository into your Colab environment:
   ```python
   !git clone https://github.com/yeasin097/Leaf-Identification-CNN.git
   ```
3. Navigate to the project directory:
   ```python
   %cd Leaf-Identification-CNN
   ```
4. Install the required dependencies:
   ```python
   !pip install -r requirements.txt
   ```

## Usage

1. Upload a dataset of leaf images to your Colab environment and organize it into `train` and `test` folders.
2. Train the model:
   ```python
   !python train.py
   ```
3. Test the model using new images:
   ```python
   !python test.py --image path_to_image.jpg
   ```

## Results

- Achieved high accuracy in recognizing leaf species.
- Visualized training progress and performance metrics.
