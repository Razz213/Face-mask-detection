# Face-mask-detection


# Face-mask-detection


## Working environment

This code was run in colab environment, so only needed dependencies are explicitly installed here (check requirement.py). Colab you can import an image dataset, train an image classifier on it, and evaluate the model, all in just <a href="https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/quickstart/beginner.ipynb">a few lines of code</a>. Colab notebooks execute code on Google's cloud servers, meaning you can leverage the power of Google hardware, including <a href="#using-accelerated-hardware">GPUs and TPUs</a>, regardless of the power of your machine. All you need is a browser.


Colab is used commonly by the machine learning community with applications including:
- Getting started with TensorFlow
- Developing and training neural networks
- free GPU/TPU training
- Creating tutorials

For more information on how to use cloab for a machine learning project, see the <a href="#machine-learning-examples">machine learning examples</a> below.


## Free GPU

Colab provides you with a free and powerful GPU (Nvidea K80 or P100). 

You'll need to enable GPUs for the notebook:

- Navigate to Edit→Notebook Settings
- select GPU from the Hardware Accelerator drop-down


## Training on a custom dataset Pipeline

1. Annotate the dataset.
2. Read the dataset into dictionaries for each image.
3. register the training/testing/validation splits.
4. Train the model
6. Check performance and metrics on training data.
7. Check performance and metrics on validation data.
8. Deploy the model (ideally)
