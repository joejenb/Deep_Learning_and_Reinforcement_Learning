## Overview
Project can be split into two parts: Deep Learning and Reinforcement Learning. Code and examples are given for both of these. A report is also given for the Deep Learning section.

## Deep Learning
For the Deep Learning component we were tasked with creating a generative model of white, winged horses – only having access to
the STL-10 and CIFAR-10 data sets. I chose to implement a VQ-VAE architecture, fitting a Pixel-CNN prior over interpolations
between latent embeddings of white horses and white birds. An example of a generated image is given below. For more details of the theory used please see 'pegasus-paper.pdf'.

![Pegasus](https://user-images.githubusercontent.com/30124151/188335297-690601a6-048c-4bb7-8baf-bd34129b7657.PNG)

## Reinforcement Learning
For the Reinforcement Learning component we were tasked with creating an agent that could play the atari game 'Gravitar'. I based my implementation largely around deepminds rainbow paper. An example run can be seen below.


https://user-images.githubusercontent.com/30124151/188335563-1acb8eeb-8dc4-4e6b-a8c3-bcb2bb725747.mp4

