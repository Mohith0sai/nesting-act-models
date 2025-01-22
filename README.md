# Project: Nesting Classical Actuarial Models into Neural Networks

This repository contains the implementation and resources for integrating Generalized Linear Models (GLMs) into neural network architectures to enhance predictive accuracy and computational efficiency in insurance claims modeling.

## Aim
The project aims to demonstrate the Combined Actuarial Neural Network (CANN) approach using the French motor third-party liability insurance dataset. It focuses on improving the handling of categorical data through embedding layers and leveraging GLM initialization for better training efficiency.

## Contents

### Files and Folders
- **`data/`**: Contains the French motor third-party liability insurance dataset.
- **`notebooks/`**: Jupyter notebooks showcasing the step-by-step implementation of the CANN approach.
- **`src/`**: Source code for the models, including:
  - GLM implementation
  - Neural network architecture with embedding layers
  - Model training and evaluation scripts
- **`results/`**: Outputs and performance metrics from the experiments.
- **`README.md`**: Overview and instructions for the project.

## Key Features
- **GLM Initialization**: Leverages parameters from GLMs to initialize the neural network, enhancing computational efficiency.
- **Embedding Layers**: Efficiently handles categorical variables, reducing dimensionality compared to one-hot encoding.
- **Real-World Dataset**: Uses the French motor third-party liability insurance dataset to validate the model.
- **Improved Performance**: Demonstrates superior predictive performance over traditional GLMs.

## Prerequisites

### Dependencies
The project requires the following Python packages:
- `tensorflow` (for neural networks)
- `keras` (for model building)
- `numpy` (for numerical operations)
- `pandas` (for data manipulation)
- `matplotlib` (for visualization)
- `statsmodels` (for statistical modelling)


## Results
- The CANN approach showed a significant reduction in out-of-sample loss compared to traditional GLMs.
- Embedding layers improved the handling of categorical features, leading to more efficient and accurate predictions.

## Citation
If you use this repository, please cite:

```
Jürg Schelldorfer and Mario V. Wüthrich, "Nesting Classical Actuarial Models into Neural Networks," Swiss Association of Actuaries, January 2019.
```

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or contributions, please contact:
- Mohith (mailto:donthumohithsai@gmail.com)
- LinkedIn: [Mohith Sai Kumar](https://www.linkedin.com/in/dounth-mohith-sai-kumar-b3682524b/)

