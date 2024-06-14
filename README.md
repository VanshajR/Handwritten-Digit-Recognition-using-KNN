# Handwritten Digit Recognition using KNN

## Description

This project is a data analysis task that uses the K-Nearest Neighbors (KNN) algorithm to classify handwritten digits. The model is trained on a `data.csv` file, which contains pixel data of handwritten digit images. The trained model is then used to analyze a `test.csv` file, and the results, including the confusion matrix and accuracy, are displayed.

## Installation

To run this project, you need to have the following libraries installed:

- Python 3.x
- NumPy
- Pandas
- scikit-learn
- Matplotlib

You can install these dependencies using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```
## Usage

1. **Clone the repository or download the notebook** to your local machine.

2. **Prepare the data**:
   - Ensure you have `data.csv` and `test.csv` files in the same directory as the notebook. These files should contain the pixel data for training and testing respectively.

3. **Run the notebook**:
   - Open the notebook in Jupyter Notebook or Jupyter Lab.
   - Execute the cells sequentially to train the KNN model and analyze the test data.

## Data

- `data.csv`: This file contains the training data with pixel values for the handwritten digit images.
- `test.csv`: This file contains the test data which will be used for evaluating the KNN model.

## Results

The notebook will output the following results:
- A confusion matrix displaying the performance of the model.
- The accuracy score of the model.
- Other relevant metrics and visualizations.

## Author

This project was created by Vanshaj Raghuvanshi.
