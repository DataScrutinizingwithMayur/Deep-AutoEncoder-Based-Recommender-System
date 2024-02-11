# Deep-AutoEncoder-Based-Recommender-System

## Overview
The Deep-AutoEncoder-Based-Recommender-System is a machine learning project aimed at building a recommendation system using deep learning techniques. It utilizes Singular Value Decomposition (SVD) for reducing the sparsity in the rating matrix and AutoEncoders for prediction, trained with a Masked Mean Square Error (MMSE) loss function. The system focuses on the MovieLens dataset, which involves user ratings for movies.

## Features
- **SVD Decomposition:** Reduction of sparsity in the rating matrix to improve recommendation quality.
- **Deep Learning Approach:** Utilization of AutoEncoders trained with a specialized MMSE loss function for accurate prediction of user preferences.
- **Dataset:** Employment of the MovieLens dataset, providing a rich source of movie user ratings for training and validation.
- **Cost Function:** Application of MMSE to evaluate and minimize prediction errors during training.

## Requirements
- Python 3.x
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Seaborn


## Code Structure
- **Data Preparation:** Scripts for preparing the training and validation datasets from the MovieLens dataset.
- **Model Definition:** Definition of the AutoEncoder architecture and the custom MMSE loss function.
- **Training:** Training loop for the AutoEncoder model on the prepared dataset.
- **Evaluation:** Evaluation of the model performance using the validation set.

## Contributing
We welcome contributions to improve the Deep-AutoEncoder-Based-Recommender-System project. Please feel free to submit pull requests or open issues to discuss proposed changes or enhancements.

## Acknowledgments
- MovieLens dataset for providing the data used in this project.
- PyTorch team for the deep learning framework used to build the model.
