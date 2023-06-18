# Simple Diffusion

This repository contains a Jupyter notebook for a simple diffusion model implemented in PyTorch.

### Background
Theoretical background can be found in [Denoising Diffusion Probabilistic Models [1]](https://arxiv.org/abs/2006.11239). Inspiration by [DeepFindr's "Diffusion models from scratch in PyTorch"](https://youtu.be/a4Yfz2FxXiY) and [Outlier's "Diffusion Models | PyTorch Implementation"](https://youtu.be/TBCRlnwJtZU).

### Implementation
The model is based on [minDiffusion](https://github.com/cloneofsimo/minDiffusion). Sinusoidal time step embeddings are taken from [Hugging Face Blog](https://huggingface.co/blog/annotated-diffusion). 

The model was trained on a small batch to prove it was implemented correctly. Because of this no model is provided in the repository. Tangible results can be expected after 3000 epochs on one batch of 32 images from [CIFAR-10 [2]](https://www.cs.toronto.edu/~kriz/cifar.html) image set. This endeavour takes around 45 minutes on a GTX 1650.

### Showcase
Batch of images sampled using the test model:

![Sampling using the model](sample_test.png)

### References
<a id="1">[1]</a> 
Denoising Diffusion Probabilistic Models;
Jonathan Ho and Ajay Jain and Pieter Abbeel;
2020;
2006.11239;
arXiv;

<a id="2">[2]</a> 
CIFAR-10 (Canadian Institute for Advanced Research);
Alex Krizhevsky and Vinod Nair and Geoffrey Hinton;
http://www.cs.toronto.edu/~kriz/cifar.html