# CTF Workshop Tutorial

This repository contains codes for the CTF Workshop tutorial of the AI Intstitute in Dynamic Systems. Please download or clone the repository for running the notebooks on your machine. Otherwise, every notebook has a link to Google Colab. 

# Outline

### Part 1: Introduction to Deep Learning - 9:00-11:00AM (Joe Bakarji)
- Introduction to Deep Learning
- Time-delay embedding and Takens' theorem
- Introduction to PyTorch
- The Lorenz system
    - The Hankel matrix
    - Approximating Takens' diffeomorphism
    - Autoencoders
    - Linear and nonlinear dominant time-modes

- Practice Examples:
    - Surrogate model of the diffusion equation solution: u(x, t)
    - Fit the model $\mathbf x_{i+1}=\mathbf f(\mathbf x_i)$ with a fully connected network.


### Part 2: Recurrent Neural Networks - 1:00PM-2:30PM (Jan Williams)
- Prevalence of sequential data in dynamical system applications
- Recurrent neural networks for time series and forecasting
- Mathematical formulation of generic RNNs (with focus on RNN's)
- Barebones implementation of vanilla RNN for forecasting periodic univariate data 
- Mathematical formulation of LSTMs 
- Time delay embeddings using recurrent layers and Lorenz, $x_{i+1}= f(x_i, x_{i-1}, ... x_{i-k})$.
- Reconstruct and/or forecast sea-surface temperature from limited sensor measurements using LSTMs


### Part 3: Pruning - 3:00PM-4:30PM (Olivia Thomas)
- Why sparsify neural networks? 
    - The importance of Regularization 
    - Reducing the memory footprint
- Sparsification methods 
    - traditional regularization approaches
    - Defining a sparse architecture
    - Pruning
- Practice problems


