# FlowerRecognizerAI

A neural-network-based flower recognition project designed to classify flowers from a trained dataset. The current project description indicates support for **three flower types**.

## Overview

FlowerRecognizerAI explores image classification using a neural network. The network is trained on examples from three flower categories and then used to recognize flowers belonging to those categories.

## Features

- Neural-network-based flower recognition
- Training using a dataset containing three flower classes
- Classification focused on the three trained categories
- Visual Studio solution for working with the project

## Repository structure

```text
FlowerRecognizerAI/
├── Flower_Recognition/          # Main project source and associated files
├── Flower_Recognition.sln       # Visual Studio solution
├── Flower recognizer_algo.pdf   # Algorithm documentation
├── Debug/                       # Debug build artifacts
├── .vs/                         # Visual Studio local files
└── README.md                    # Project documentation
```

The repository also contains a Visual Studio database file (`Flower_Recognition.VC.db`).

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/HadarPur/FlowerRecognizerAI.git
   cd FlowerRecognizerAI
   ```

2. Open `Flower_Recognition.sln` in Microsoft Visual Studio.
3. Inspect the solution's project settings and configure any required dependencies and dataset paths.
4. Build the solution using the configuration and platform supported by the project.
5. Run the compiled program according to its input requirements.

> **Note:** The precise compiler requirements, external dependencies, dataset format, and runtime inputs have not been verified. Consult the source code and `Flower recognizer_algo.pdf` before building or running the program.

## How it works

At a high level, the workflow consists of:

1. **Dataset preparation:** Collect labeled examples from three flower categories.
2. **Training:** Train a neural network to learn distinctions between those categories.
3. **Recognition:** Provide a flower sample to the trained network for classification.
4. **Prediction:** Obtain a classification among the supported flower types.

The exact network architecture, preprocessing steps, and training procedure should be confirmed from the implementation and algorithm document.

## Current scope and limitations

- The project currently describes recognition of **three flower types**.
- Recognition of other flower categories is not established.
- No verified accuracy metrics, model architecture, or dataset provenance are available in the repository's short public description.

## Further documentation

See [`Flower recognizer_algo.pdf`](Flower%20recognizer_algo.pdf) for the project's algorithm documentation.[](https://github.com/HadarPur/FlowerRecognizerAI)
