# Sound-Source Localization

## Project Aim

This project aims to locate sound direction in both azimuth (left-right) and elevation (top-bottom) angle.
The author used four neural network architectures in performing the localization: Multi Layered Perceptron, Convolutional Neural Network, 
Recurrent Neural Network, and Bidirectional Recurrent Neural Network. The localization is formularized as classification of 15 different class/position.

## Robot

The robot used in this experiment is displayed by figure below. A microphone is mounted in each of the robot's two ears to mimic human hearing system.

<p align="center">
  <img src="https://i.ibb.co/Fnb4hDZ/20190621-161725.jpg" width="350" title="hover text">
</p>


## Dataset

The project sound dataset can downloaded from here:

https://drive.google.com/drive/folders/1g2mrCKddu0BRWeoriNuV1fJzEWUmmzTE?usp=sharing

## File Usage

* cfg.ipynb : define audio preprocessing class
* eda.ipynb : visualize input data, clean or resample audio files if necessary
* model.ipynb : train neural network
* predict.ipynb : test the neural network


## Note

This project is heavily inspired by Seth Adam's tutorial on instrument classification. 
The links to Seth's tutorial and project are:
 https://www.youtube.com/watch?v=Z7YM-HAz-IY&list=PLhA3b2k8R3t2Ng1WW_7MiXeh1pfQJQi_P
 
 https://github.com/seth814/Audio-Classification

This project is written in Python with Numpy, Tensorflow, and Keras frameworks. The file are in ipynb format or Jupyter Notebook's document. 
