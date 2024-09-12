# Image-to-Image Translation

This project explores unsupervised image-to-image transformation using Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs).
The model learns a joint distribution of images across different domains by utilizing images from the marginal distributions in individual domains.
Since infinite joint distributions can result from given marginal distributions, inferring the joint distribution without additional assumptions is challenging.

To address this, I assume a shared latent space and propose an unsupervised image-to-image translation framework based on Coupled GANs. 
The framework is compared with competing approaches and demonstrates high-quality image transformation results on various challenging tasks,
including lab interior images and mobile phone image transformation. The framework is also applied to domain adaptation, achieving state-of-the-art
performance on benchmark datasets.

**Dataset**: I used my own dataset, provided by IIT Madras.

If you'd like to try this or need more information, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/aditya-dixit-iiti/).

