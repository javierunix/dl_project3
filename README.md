Synopsis

Recurrent Neural Network (RNN) for text generation. Its goal is to generate text using part of the Simpsons dataset of scripts from 27 seasons. The Neural Network we will ll build will generate a new TV script for a scene at Moe's Tavern, with very hilarious results as you will see.

Code example

You will find 4 programs. The main one is "dlnd_tv_script_generation.ipynb". The aim of "dlnd_tv_script_generation.html" is to help to visualize the code, right in your browser. On the other hand, "helper.py" and "problem_unittests.py" are auxiliar programs needed to run the image classificator. We assume that all the scripts have to be in the same directory, otherwise, you will have to indicate the path.

Motivation

This project is part of the wonderful Deep Learning Foundations Nanodegree, of Udacity. You just can download it and running, but in that case you would not learn more. It is and educational tool, and the more of you would be in it more useful will became.

Installation

I order tu run you will need python 3.5 in your computer, with the Google Tensorflow library for Machine Learning installed. Probably, in python 2.7 this programs will not work, since they have not implementened and test in this version. If you have a GPU Cudda Compatible, you can just run locally the program. If not this kind of Neural Networls are extremely low, when running, on CPU. I strongly recommend use a Cloud Computing service, such as AWS.

Tests

Just run the code "dlnd_tv_script_generation.ipynb" in a Anaconda Jupyter Notebook, with all the dependencies installed. This is a first version and it has been trained with a relatively small dataset. Otherwise it will take a very long time to train. The achieved loss is about 0.650, what is pretty decent.

Javier Guijarro (Creative Commons license)