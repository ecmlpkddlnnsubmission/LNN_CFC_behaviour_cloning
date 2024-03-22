# Finetuning of Continuous Time Recurrent Neural Networks on Behaviour Cloning using Closed-form Continuous-Time Neural Networks and Liquid Time Constant Networks


## Functions

- `run_test`: This function is used to run the test on the model with various parameters like learning rate, epochs, units, etc. It also includes the creation of the environment using gym and ale_py, and the training and validation data loaders.

- `visualize`: This function is used to visualize the Atari game and play it endlessly.

## Model

The model used in this project is a Convolutional Neural Network (CNN) with various layers including `ImpalaConvBlock` and `ConvBlock`. The model is compiled with the Adam optimizer and SparseCategoricalCrossentropy loss function.

## Setup

To run this project, you need to have Python, TensorFlow, gym, and ale_py installed. You can install these using pip:

```sh
pip install -r requirements.txt
```

Then, you can run the Jupyter notebook or the Python script as per your requirement.


## LTC model in action
<video width="800" height="450" autoplay muted loop>
    <source src="ltc-atari-breakout.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
