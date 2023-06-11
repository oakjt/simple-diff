#### Simple diffusion model


This repository contains a Jupyter notebook for a simple diffusion model implemented in PyTorch.
The model is based on [minDiffusion](https://github.com/cloneofsimo/minDiffusion). 
Theoretical background from [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239).
Inspiration from [DeepFindr's "Diffusion models from scratch in PyTorch"](https://youtu.be/a4Yfz2FxXiY) and [Outlier's "Diffusion Models | PyTorch Implementation"](https://youtu.be/TBCRlnwJtZU). Sinusoidal time step embeddings from [Hugging Face Blog](https://huggingface.co/blog/annotated-diffusion). 

This implementation serves strictly for education purpose. Models are not included. The test model was trained for 3000 epochs on one batch of 32 images from [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) image set. 

Batch of images sampled using the test model:

![Sampling using the model](sample_test.png)
