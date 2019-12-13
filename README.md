# Lightweight, Semi-Automatic Variability Extraction: A Case Study on Scientific Computing (Supplementary Website)

Authors: Alexander Grebhahn, Christian Kaltenecker, Christian Engwer, Norbert Siegmund, Sven Apel
Journal: Empirical Software Engineering
Corresponding Author: Christian Kaltenecker (Saarland University, kaltenec@cs.uni-saarland.de)

This repository contains the supplemental material for the paper 'Lightweight, Semi-Automatic Variability Extraction: A Case Study on Scientific Computing'.
In particular, the supplemental material consists of the following:
* Implementation of our approach (VORM)
* Results of the evaluation

We supply a `Dockerfile` to deploy and execute our approach in a docker container. 
First, make sure to clone the repository.
To set up the Docker container, make also sure that you have properly installed Docker (https://docs.docker.com/get-started/) and the Docker daemon is running.
Afterwards, the image can be built by invoking the following command inside the repository.

```
sudo docker build -t variabilityextraction ./
```
After building the image, an interactive session in a docker container can be started by:

```
sudo docker run -ti variabilityextraction
```

