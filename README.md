# Machine-Learning-ENSTA
Machine Learning Course (MI201) Project

## 📋 Description
The goal of the project is to implement a learning approach capable to identify the toppings of a pizza, using real and synthetic data. The synthetic data is composed by pizza drawings, while the real one is real pizzas.
The data can be downloaded from the [page](http://pizzagan.csail.mit.edu/).

In this case, the problem is a multi-label prediction: each image may be characterized by several labels. Therefore, to solve this problem we worked on raw data and build the label predictor directly.

We did a fine tuning of a pre-learned neural network (ResNet), in other words, use the weights of a trained neural network to initialize a new model trained on data from the same images.

## 🛠️ Software used

This project was implemented in Python.

## ✒️ Authors

- Arthur Coelho Ruback:
    - [![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/arthur-ruback)

- Gustavo Jodar Soares:
    - [![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/Gustavo-Jodar)

- Matheus SANTOS SANO:
    - [![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/matsano)

We would like to thank our professors Mr. Adrien Chan Hon Tong, Mr. Gianni Franchi and Mr. Stéphane Herbin for the knowledge taught in Machine Learning Course at [ENSTA Paris](https://www.ensta-paris.fr/) which were essential for the realization of this project.
