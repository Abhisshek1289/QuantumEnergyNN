# Quantum Energy Level Prediction using Neural Networks

This project uses a neural network to predict the energy levels of a quantum harmonic oscillator based on its frequency (ω) and quantum number (n).

## Project Overview

The quantum harmonic oscillator is a fundamental model in quantum mechanics with energy levels given by:  
\[ E_n = \hbar \omega (n + 0.5) \]

In this project, synthetic data was generated using this formula, with added noise to simulate measurement imperfections. A neural network was then trained to learn the relationship between inputs (ω, n) and the noisy energy levels.

The model was built using Python and TensorFlow and trained on Google Colab.

## Features

- Generates synthetic quantum energy level data with noise  
- Implements a feedforward neural network with two hidden layers  
- Predicts energy levels given oscillator frequency and quantum number  
- Visualizes predictions versus actual values with plots  
- Saves the trained model for future use

## Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab

## How to Run

1. Open the notebook in Google Colab.  
2. Run all cells sequentially.  
3. View the output plots and saved model files.

## Author

Abhishek Goel 
Date: May 2025
