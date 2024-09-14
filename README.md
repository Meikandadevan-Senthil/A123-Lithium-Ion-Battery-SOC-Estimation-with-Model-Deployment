# Seq2Seq Network for Estimating the State of Charge of Li-Ion EV Batteries

This repository contains the code for a **Sequence-to-Sequence (Seq2Seq) network** designed to estimate the **State of Charge (SOC)** of Lithium-Ion Batteries (LIBs), specifically for **Electric Vehicles (EVs)**. The project integrates advanced data-driven methodologies to achieve high accuracy in SOC estimation and includes a user-friendly **Graphical User Interface (GUI)** for real-time SOC predictions.

## Project Overview

Lithium-Ion batteries are crucial in various applications due to their high energy density and longevity. However, accurately estimating the SOC remains a challenge due to the complex dynamics of LIBs. This project proposes a novel Seq2Seq architecture incorporating:

- **Multilayer Perceptron (MLP) Encoder**
- **Gated Recurrent Units (GRU) Decoder**

The model is trained on benchmark datasets from the **Centre for Advanced Life Cycle Engineering (CALCE)**, specifically for **A123 LIBs**, under a 30°C temperature profile. The results show SOC estimation accuracy with:

- **Root Mean Squared Error (RMSE)**: 0.296
- **Mean Absolute Error (MAE)**: 0.25

## Features

- **Seq2Seq Architecture**: Combines MLP encoder with GRU decoder for improved SOC estimation.
- **Data-driven Approach**: Utilizes comprehensive benchmark datasets from CALCE.
- **Real-Time SOC Prediction**: GUI designed to provide real-time SOC predictions for practical use.

## Requirements

- Python 3.x
- TensorFlow / PyTorch 
- Required libraries: NumPy, pandas, matplotlib, etc.
- Tkinter

## Results

- Achieves **RMSE** of 0.296 and **MAE** of 0.25 for SOC estimation under a 30°C temperature profile.
  
## Future Work

- Extending the model to handle different temperature profiles.
- Improving the real-time prediction accuracy for various LIBs types.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Centre for Advanced Life Cycle Engineering (CALCE) for providing the benchmark datasets.
