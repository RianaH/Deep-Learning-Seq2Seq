
# Seq2seq Neural Spike Pattern Analysis

## Project Overview

Neuroscientists have devoted significant time and effort to understanding how neural activity determines behavior; however, they have historically lacked analytical tools that can account for the inter-regional dynamics underlying behavioral output. Seq2seq models, which use deep learning approaches to translate one time series to another, are a promising method of capturing these inter-regional dynamics and relating them to behavior.

The present project uses a Seq2seq model to learn the latent dynamics underlying inter-regional covariation in neural spike patterns in two brain regions, the hippocampus (HC) and the prefrontal cortex (PF), and then uses these latents to predict rat foraging behavior.

## Results

- **Latent Dynamics**: Successfully learned the underlying low-dimensional latent dynamics that define the relationship between neural spiking in the HC and the PF.
- **Neural Spiking Prediction**: Utilized HC time series data to predict PF neural spiking.
- **Behavioral Prediction**: Achieved mixed results on the task of behavioral prediction from these latent dynamics. The Seq2seq model often outperformed the no-information rate (predicting the majority class) but not to a statistically significant degree when compared to competitors (a random forest model, a deep neural network, and a model that always predicted the majority class).

## Code and Implementation

The Seq2seq model code is implemented in Python using libraries such as PyTorch and Pandas. The implementation includes:

1. Extracting and preprocessing data for the Seq2seq model.
2. Building and training the Seq2seq model.
3. Comparing the Seq2seq model's performance against a Random Forest model and a Deep Neural Network model.

## Contributions

- **Seq2seq Model**: Developed by Riana Hoagland.
- **Random Forest and Deep Neural Network Models**: Developed by a classmate for comparison purposes.

## License

This project is currently in progress and is being continued. The code and ideas are protected and should not be used or reproduced without permission. The data utilized in this project is not pubically available. 
