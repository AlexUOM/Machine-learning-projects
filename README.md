# Machine Learning Showcase Repository

## Overview

This repository serves as a showcase of machine learning skills, featuring two distinct projects. The first project focuses on image processing and recognition, utilizing the MNIST database to train and evaluate a random forest model capable of recognizing handwritten digits. The second project employs various unsupervised learning methods to analyze a dataset containing arrest statistics per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973.

### Repository structure

The code for data preprocessing, model training, tuning, and evaluation is found in **/projects_code**.

## Project 1: MNIST Digit Recognition
### Objective

Develop and evaluate a random forest model for recognizing handwritten digits using the MNIST database.

## Project 2: US States Arrest Statistics Analysis
### Objective
Apply unsupervised learning techniques to analyze arrest statistics data for assault, murder, and rape in US states in 1973.

### Workflow

1. Clone the repository:

    ```bash
    git clone https://github.com/AlexUOM/Machine-learning-projects.git
    cd Machine-learning-projects
    ```

2. Navigate to the project directory:

    ```bash
    cd projects_code
    ```

3. Execute the main script for model training and evaluation:

    ```bash
    python project1_image_recognition.py
    ```
    or
   
   ```bash
    python project2_arrests_analysis.py
    ```

## Dependencies

- Python 3.x
- Required Python libraries:

  ```plaintext
  numpy==1.21.0
  pandas==1.3.0
  tqdm==4.61.1
  matplotlib==3.4.3
  scikit-learn==0.24.2
  seaborn==0.11.2
  keras==2.4.3

## Analysis Pros and Cons 

- **MNIST Digit Recognition:**
  - Pros: Achieves high accuracy, suitable for digit recognition tasks.
  - Cons: May be computationally intensive during training.

- **US States Arrest Statistics Analysis:**
  - Pros: Reveals patterns and relationships in the dataset.
  - Cons: Interpretability may vary depending on the clustering method used.

## Contributing

Contributions, feedback, and suggestions are welcome. Please refer to the `/CONTRIBUTING.md` file for guidelines.

## Acknowledgments

Thank you to the developers of the MNIST database and contributors to the US states arrest statistics dataset. Special thanks to the machine learning community for inspiration and support.
