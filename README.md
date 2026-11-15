# Trade-off between Average Pauli weight and Quantum Fourier entropy

This repository contains a Jupyter Notebook for reproducing the red curve in a schematic figure from our paper.

The curve illustrates the trade-off between the average Pauli weight (${W(O)}$) and the scaled quantum Fourier entropy ($S_a(O)/\lambda$).


## Contents
- `WS_trade-off.ipynb`: Computes and plots the trade-off curve using its analytical parametrization.


## Requirements
- Python 3
- Numpy
- Matplotlib
- Jupyter Notebook


## Usage
Open `WS_trade-off.ipynb` in Jupyter Notebook and run all cells in order.

The notebook generates `ws_curve.pdf` in the working directory.

**Note**:
The generated PDF contains only the red curve and basic axis labels.
The other elements of the published schematic figure were added separately.

No external datasets or random sampling are required.
