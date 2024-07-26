# Creating Multi-Task Models with Keras

**Author:** Dr. Ronny Guendel  
**Date:** 26th July '24

---

## Project Overview

In this project, we utilize Keras and TensorFlow to build a deep neural network capable of multi-task learning. The model is designed to identify two features simultaneously from an image: the number and the predominant color. We use the MNIST dataset for training and evaluation. The project can be executed in Google Colab or Jupyter Notebook, with a caution that TensorBoard might present issues in some environments.

---

## Visual Examples

### Example 1: Number 3 with Noise
![Number 3](./fig/num_3.png?raw=true)

### Example 2: Number 7 with Noise
![Number 7](./fig/num_7.png?raw=true)

---

## Model Design

The following diagram illustrates the architecture and flow of the deep neural network used in this project:

![Model Architecture](./fig/model.png?raw=true)

---

## Prediction Samples

Here are some sample predictions made by the model:

![Predictions](./fig/prediction_numbers.png?raw=true)

---

## Acknowledgements

Special thanks to the Coursera Guided Project for the foundation and inspiration:  
[Creating Multi-Task Models with Keras](https://www.coursera.org/projects/multi-task-models-keras)
