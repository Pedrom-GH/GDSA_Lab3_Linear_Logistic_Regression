# Lab 3 · Linear & Logistic Regression

The two basic building blocks of machine learning, implemented and trained with PyTorch.

**File:** [`03_linear_logistic_regression.py`](03_linear_logistic_regression.py). It is a Colab notebook exported as a Python script, so the Markdown cells appear as comments and docstrings.

## What I worked on

- Generating noisy synthetic data with separate training and test sets
- Linear regression as an `nn.Module` with two learnable parameters (`nn.Parameter` for w and b)
- Training with backpropagation, SGD and an MSE cost, with shuffling and per-epoch updates
- Logistic regression on two 2-D Gaussian classes (`nn.Linear` + sigmoid) trained with binary cross-entropy
- Predicting new points with the trained regressor and plotting the learned line and the 3-D logistic probability surface

## Stack

Python · PyTorch · Matplotlib · NumPy · Google Colab

## How to run

Open the script in [Google Colab](https://colab.research.google.com/) or run it locally:

```bash
pip install torch numpy matplotlib
python 03_linear_logistic_regression.py
```

## Credits

Lab template created by Santiago Pascual, updated by Xavier Giró-i-Nieto (UPC, 2019), with parts based on work by Víctor Campos and Daniel Fojo as course material. The original authors are credited at the top of the file. The exercise solutions are my own work.

---
Part of my [GDSA labs](https://github.com/Pedrom-GH/GDSA_PEDRO) · B.Sc. in Telecommunications Systems Engineering, UPC – ESEIAAT · Pedro Muñoz Álvarez
