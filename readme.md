# Transformer implementation and example training

Hello there! In this notebook I have implemented a custom Transformer model for sentiment analysis using TensorFlow and Keras. In this project, I have tried to apply as much of my machine learning knowledge as possible. The implementation may not be perfect, nevertheless I am proud of it as most of it is based on my own understanding and ideas. Notably might be the implemention of the attention algorithm using the einsum operation. I plan to introduce further improvements here and there. Additionally, I intend to deploy the trained model in an end-to-end MLOps pipeline, similar to what I have done in my other projects.

## Usage

The notebook demonstrates:
1. Loading and preprocessing the IMDB dataset
2. Configuring and creating a custom Transformer model
3. Training the model on the dataset
4. Evaluating the model's performance
5. Saving and loading the trained model
6. Using the model for inference on new text

## Requirements

- TensorFlow
- Transformers (Hugging Face)
- Datasets (Hugging Face)
- Pandas
- NumPy

Note: This implementation is for educational purposes and may not be optimized for production use.