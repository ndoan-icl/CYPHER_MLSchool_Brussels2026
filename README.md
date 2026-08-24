# CYPHER Training School - Scientific Machine Learning Methods for Digital Twins (07/09/2026-09/09/2026)

This repository contains the hands-on jupyter notebooks for the session on 09/09 of the CYPHER Training School "Scientific Machine Learning Methods for Digital Twins".

This repository contains:

1. [The slides](Slides/CYPHER_ML_School_2026.pdf) presented during the session. Slides related to the exercises are available [here](Slides/CYPHER_ML_School_2026_Exercises.pdf).
2. The various datasets used during the session
	- The dataset for the System Identification notebook based on a laminar slit flame excited with a broadband signal
	- The [Lorenz system dataset](Lorenz_data/LorenzSys_Lorenz_data.npz) for the example notebook on the Lorenz system
	- The [broadband forcing and heat release rate signals](Flame_data/) for the flame dynamics learning exercise
	- The [validation flame describing functions](Validation_data/Flame_valid_data.h5) containing the frequency response of the flam

## Description
The repository contains five different notebooks:

1. The [System Identification notebook](01_SystemIdentification.ipynb) which describes how to perform system identification on a flame dynamics dataset under linear excitation. This notebook is from the group of Prof. Polifke at TU Munich. The original version can be found [here](https://gitlab.lrz.de/tfd/system-identification-tutorial/).
2. The [MLP-based Lorenz system notebook](01_MLP_Lorenz.ipynb) where a feedforward neural network is developed to learn the dynamics of the Lorenz system.
3. The [RNN-based Lorenz system notebook](01_LSTM_Lorenz.ipynb) where a long short-term neural network is developed to learn the dynamics of the Lorenz system.
4. The ESN-based Lorenz system notebook where an echo state network is developed to learn the dynamics of the Lorenz system.
5. The [flame dynamics notebook](05_FlameDynamics.ipynb) which describes how to read the flame dynamics dataset.


The first four notebooks are fully complete and used for illustrative purposes.
The last notebook will be used as a starting point for the exercise sessions.

## Maintainers
[@ndoan-icl](https://github.com/ndoan-icl/).

## License

[MIT](LICENSE) © Nguyen Anh Khoa Doan
