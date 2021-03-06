# Tutorial Materials for Generative Adversarial Nets (GANs)

A general introduction of GAN for the lab seminar. Here are some generated samples:

![image](https://github.com/wayne391/GAN-tutorial/blob/master/ref/samples/cifar10_sngan.png)
![image](https://github.com/wayne391/GAN-tutorial/blob/master/ref/samples/mnist_acgan.png)
![image](https://github.com/wayne391/GAN-tutorial/blob/master/ref/samples/tab_wgan_gp_small.png)

---

This repository is organized as the following:

### pytorch
pytotch (version 1.0) implementation. WGAN-gp
    

### datasets
Basic datasets.
For images, we have cifar-10 and mnist.
For the music, we offer the 'tab' dataset. We represents the music in so called 'piano-roll' fromat,
which is a binary and sparse tensor.

### ref
paper backup

### slides
Slides for related works.

### topics
   Implementation of the aforementioned topics in the slides. All are written in Tenseoflow **(< 1.0)**.
- single image genration:  
    SN-GAN, WGAN-GP  

- conditional generation:    
    concatenation, ACGAN  
