---
layout: page
title: Projects
---

Discover the projects I worked on.

## Personnal projects.

---

### Genetic algorithm for the Traveling Salesman Problem

[View notebook](https://github.com/jldiazthiele/ga-tsp/blob/main/ga_tsp.ipynb)

This project is an implementation of a genetic algorithm to approximate a solution to the Traveling Salesman Problem. A genetic algorithm draws inspiration from the thoery of evolution by maintainig a set of possible solutions (the population) and applying successive reproduction, mutation, and selection steps to approximate a solution by optimising a given fitness function. This project is informed by the book [Introduction to Evolutionary Computing](http://www.evolutionarycomputation.org/).

Here's an example run of the algorithm:
![Traveling Salesman Animation](https://jldiazthiele.github.io/assets/img/tsp_animation.gif)

## University projects.
---

### Model-free reinforcement learning for focal plane wavefront control

The aim of this project was to train a reinforcement learning agent to control the deformable mirror of an adaptive optics system from focal plane images alone (that is, the images recorded by the camera). Adaptive optics systems aim to correct phase aberrations that affect the images recorded by the camera of a telescope to reach the optimal performance of that telescope. This project was done in collaboration with researchers from the department of astrophysics of the university of Liège in the context of my Master's thesis.

The project involved developping the surrounding simulation of an adaptive optics system and the associated reinforcement learning environment, researching and implementing suitable architectures for the policy and value networks as well as the feature extractor of the agent, and training and evaluating reinforcement learning agents. The reinforcement learning agents achieved near optimal corrections on average, showing the effectiveness of the reinforcement learnign approach for focal plane wavefront control.


