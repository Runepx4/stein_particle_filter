# Introdction

This code provides a Python implementation of Stein particle filter presented in the paper:

Fahira Afzal Maken, Fabio Ramos, Lionel Ott, [Stein Particle Filter for Nonlinear, Non-Gaussian State Estimation](https://arxiv.org/abs/2202.04213), RAL, 2022.
<!--https://arxiv.org/abs/2106.03287), *RAL, 2021* -->


# Installation

The code depends on PyTorch 1.6.0 or newer. 

To facilitate the overall install a shell script `pip_install.sh` is provided.  

All required packages can be installed by executing the `pip_install.sh` script.


# Running

The code is provided in the form of a Jupyter notebook. To run the code, please start the notebook via:

```
jupyter notebook
```

An environment, simulated in a [LIDAR simulator](https://github.com/RansML/simulator_lidar), is provided with the code. The code, by default, estiamtes the state of a moving robot in the given simulated environment. 