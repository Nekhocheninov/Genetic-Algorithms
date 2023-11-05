# Python Genetic Algorithms

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/Nekhocheninov/Genetic-Algorithms/blob/main/LICENSE.md)
![GitHub last commit](https://img.shields.io/github/last-commit/Nekhocheninov/Genetic-Algorithms)
[![Open in Colab](https://img.shields.io/badge/Open%20in%20Colab-Open-blue?logo=google-colab)](https://drive.google.com/file/d/1V9Xa-Tx3Zl7xktCQdRIVo36Ob83TbW5d/view?usp=sharing)

[Genetic algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm) implementation in Python.

### Running the notebook

The code was written in Python across Jupyter notebooks. It was developed in Google Colab which is a free Jupyter notebook environment that allows you to run code through a browser.

Follow [this link](https://drive.google.com/file/d/1V9Xa-Tx3Zl7xktCQdRIVo36Ob83TbW5d/view?usp=sharing) to open the notepad with this code and click on Google Colaboratory.

# Samples

Find the minimum of a function of two variables:

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_1.PNG" width="500">

Minimum point *f(x,y) = f(10,5) = 0*:

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_2.PNG" width="500">

Let us study the dependence of the size of the initial population on the maximum number of epochs. Let us take the probability of mutation equal to 1 and inversion equal to 0, and the number of chromosome splitting points in the crossing operator equal to 1.

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_3.PNG" width="800">

As would be expected, the result improves as the size of the initial population and the maximum number of epochs increase.

Let us study the influence of the number of chromosome splitting points in the crossing operator on the result for different sizes of the initial population. Let us take the probability of mutation equal to 1, and the inversion equal to 0, the maximum number of epochs is 1000.

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_4.PNG" width="800">

Increasing the number of chromosome split points at small values ​​of the initial population size increases the accuracy, but as the initial population size increases, the accuracy decreases.

Let us study the effect of mutation probability on the result for different sizes of the initial population. Let us take the probability of inversion equal to 0, the maximum number of epochs is 1000, and the number of chromosome splitting points in the crossover operator is 1.

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_5.PNG" width="800">

Judging by the table, the accuracy increases with large values ​​of the mutation probability.

Let us study the influence of the probability of inversion on the result for different sizes of the initial population. Let us take the probability of mutation equal to 1, the maximum number of epochs is 1000, and the number of chromosome splitting points in the crossover operator is 1.

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_6.PNG" width="800">

In general, judging by the table, there is no dependence. Let us check the dependence of the inversion probability on the mutation probability with an initial population equal to 1000, the maximum number of epochs is 1000, and the number of chromosome splitting points in the crossover operator is 1.

<img src="https://github.com/Nekhocheninov/GeneticAlgorithms/blob/main/img/img_7.PNG" width="800">

### Conclusion

After studying the dependencies of the algorithm parameters, the best result was obtained f(9,88,4,98) = 0.0171 with an initial population of 1000, a maximum number of epochs of 1000, the number of chromosome splitting points in the crossover operator 1, mutation probability 0.3 and reversal probability 0.5.
