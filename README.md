# Generative Adverarial Networks :computer: vs :computer:

Hi There! 👋<br/>
This is a repo where you have access to all the Jupiter Notebooks, along with some resources that made it all possible!<br/>

## Table of Contents
* [What are GANs?](#What-are-GANs?)
* [The Good Stuff](#The-Good-Stuff)
* [Acknowledgements](#Acknowledgements)
* [Connect with me](#Connect-with-me)

## What are GANs?

### TL;DR 
2 neural networks that constantly duke it out with each other in order to generate better and better content.

### A Longer Explanation:
GANs were originally proposed by Ian Goodfellow et al. in their paper: [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661). It's a facinating and quite powerful system that took the machine learning community by storm. We often see them in action whenever we come across a deepfake, or generated images. 

It works by having 2 models, G(enerator) and D(escriminator), going against each other. The G model's loss function (for backprobagation) is dependent on the performance of the D model. Thus, in order to minimize it's own loss, it tries to maximize the loss of the other model. The same is true for the D model. This causes both models, which are randomly initialized at the start, to become very good at their tasks in a short amount of time. 

Many other types of GANs exist as well. Some switch out the type of models that are used (DCGANs), while others rearange the whole architecture of the GAN (CycleGANs). 

I actually wrote a whole article aobut this! [Check it out](https://medium.com/swlh/creating-a-human-that-never-existed-65d046fe8cb3)!

## The Good Stuff
Now what we're all here for: GIFs!

<p align="center">
<img src="readme_pics/MNIST.gif" width="350"/><br/>
MNIST
</p>


<p align="center">
<img src="readme_pics/CIFAR10.gif" width="350"/><br/>
CIFAR10
</p>


<p align="center">
<img src="readme_pics/Fashion MNIST.gif" width="350"/><br/>
Fashion MNIST
</p>

<p align="center">
<img src="readme_pics/Faces.gif" width="350"/><br/>
CelebA
</p>


<p align="center">
<img src="" width="350"/><br/>
Pokemon
</p>

## Acknowledgements

I found these resources extremely useful:

* [Name](link)
* [Name](link)


## Connect with me

If you want to follow along on my journey, you can join my [monthly newsletter](https://www.subscribepage.com/g1p8w4), check out my [website](https://dicksonwu654.github.io/), and connect on [Linkedin](https://www.linkedin.com/in/real-dickson-wu/) or [Twitter](https://twitter.com/DicksonWu3) 😃
