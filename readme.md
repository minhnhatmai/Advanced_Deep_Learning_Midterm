# KMNIST Feedforward Neural Network with Adam Optimizer

This project trains a feedforward neural network on the KMNIST dataset using TensorFlow and Keras, with K-Fold cross-validation and optimizers (Adam ,AdamW and RMSProp).

## Requirements

- Python 3.7+
- pip

### Recommended: Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## Install Dependencies

Create a new cell at the beginning and run the command below to install:
```bash
pip install tensorflow tensorflow-datasets scikit-learn matplotlib pandas
```

## Run the Notebook

1. Open VS Code.
2. Install the Python and Jupyter extensions if you haven’t already.
3. Open `Midterm_Feedforward_Adam.ipynb`.
4. Run the notebook cells sequentially.

## Notes

- The code will automatically use your GPU if available.
- The notebook will display a table with accuracy, loss, and training time for each fold.

---