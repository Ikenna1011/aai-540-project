Group-4 Final Project

## Project Overview

This repository contains the final project for Group-4 in the AAI-540 course. The project focuses on applying advanced artificial intelligence techniques to solve a real-world problem.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

The goal of this project is to demonstrate the practical application of AI methodologies, including data preprocessing, model training, and evaluation. The project addresses building a custom QA dataset with Amazon SageMaker Ground Truth and Hugging Face. One challenge we faced was the substantial computational resources required by Hugging Face models, which exceeded the constraints of our lab setup.

## Features

- Comprehensive data analysis and visualization.
- Implementation of state-of-the-art machine learning models.
- Detailed performance evaluation and reporting.
- Modular and reusable codebase.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ikenna1011/aai-540-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd aai-540-project
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset and place it in the `data/` directory.
2. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
3. Train the model:
   ```bash
   python train.py
   ```
4. Evaluate the model:
   ```bash
   python evaluate.py
   ```

## Contributors

- Ikenna [GitHub Profile](https://github.com/Ikenna1011)
- Christopher Teli
- Jennifer Black

## License

This project is licensed under the [MIT License](LICENSE).
