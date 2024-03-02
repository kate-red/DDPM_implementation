# DDPM_implementation

## Overview

DDPMs are generative models that leverage the concept of diffusion processes to model the data distribution. This is an implementation of diffusion model from the paper "Differentiable Diffusion Probabilistic Models" as a final project for the course "Deep Generative Models" at the HSE University.

## Usage

1. Clone the repository:

    ```
    git clone https://github.com/kate-red/DDPM_implementation.git
    ```

2. Install the dependencies:

    ```
    pip install -r requirements.txt
    ```

3. Train the model:

    ```
    python DDPM_implementation.py
    ```

## Code Structure

- `DDPM_implementation.py`: main script containing the implementation of DDPM, training procedure, and sample generation;
- `DDPM_demo.ipynb`: a demonstration of the implemented model with examples;
- `README.md`: an overview of the project;
- `requirements.txt`: list of dependencies required to run the project.

## Acknowledgments

- This implementation is based on the paper [Differentiable Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) by Jonathan Ho, Ajay Jain, Pieter Abbeel.
