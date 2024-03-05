#  Creating anime characters using DCGANs and Keras 
### **Author : Joseph Santarcangelo, Roxanne, Junxing(J.C.) Chen

## Overview 
Generative adversarial networks (GANs)
It is a class of machine learning frameworks, first published in June 2014 [1].
GANs could generate new data following the statistic features of the data in the training set. GANs is widely used to generate new and realistic photograph that is authentic to human observers.

Convolutional networks (CNNs) has seen huge adoption in computer vision applications. Applying the CNNs to GANs models could help us in building a photo generating model. The combined method is called Deep Convolutional Generative Adversarial Networks (DCGANs).

In this lab, we will first focus on simulated data to better understand GANs.
Further, we will use the case of massive anime avatar production to introduce how to use DCGANs.
You will create anime characters like the ones below in this project.

Skills Network Logo
## Mentee Information 
- **Name:** Farhan Firmansyah
- **Program:** IBM Advanced AI

## Table of Contents 
1. Objectives
2. Setup
  - Installing Required Libraries
  - Importing Required Libraries
  - Defining Helper Functions
3. Basic: Generative Adversarial Networks (GANs)
  - Introduction
  - Toy Data
  - The Generator
  - The Loss Function GANs (Optional)
  - Training GANs
4. Deep Convolutional Generative Adversarial Networks (DCGANs)
  - Case background
  - Loading the Dataset
  - Creating Data Generator
  - Generator and Discriminator (for DCGANs)
  - Defining Loss Functions
  - Defining Optimizers
  - Create Train Step Function
  - Training DCGANs
5. Explore Latent Variables
  - Exercise 1
  - Exercise 2
  - Exercise 3

## Objectives 
After completing this lab, you will be able to:

- Understand the original formulation of GANs, and their two separately trained networks: Generator and Discriminator
- Implement GANs on simulated and real datasets
- Apply DCGANs to a dataset
- Understand how to train DCGANs
- Generate an image using a DCGAN
- Understand how changing the input of the latent space of DCGANs changes the generated image
