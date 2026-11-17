# MNIST-Handwritten-Digit-Recognition
A handwritten digit recognition neural network built from scratch using Python and NumPy.

## DATASET
This project uses the [Kaggle Digit Recognizer dataset](https://www.kaggle.com/competitions/digit-recognizer), a version of MNIST containing 42,000 labeled images of handwritten digits (28x28 pixels, grayscale). The data was prepared on Kaggle, split into training and validation sets, and saved as `prepared_data.npz`.

## How to run 
1. Download `train.csv` from the [Kaggle Digit Recognizer competition](https://www.kaggle.com/competitions/digit-recognizer/data).
2. Prepare the data (shuffle, split into training and validation sets) and save it as `prepared_data.npz`.
3. Open `MNIST-Handwritten-Digit-Recognition.ipynb` in Jupyter or Google Colab.
4. Put `prepared_data.npz` in the same folder as the notebook.
5. Run the cells in order.

## REQUIREMENTS
- Python 3
- NumPy
- Matplotlib