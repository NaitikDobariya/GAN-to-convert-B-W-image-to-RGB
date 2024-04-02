# GAN-to-convert-B-W-image-to-RGB

### Pix2Pix GAN for Image-to-Image Translation

This repository is an implementation of Pix2Pix GAN for the Image-to-Image translation task. This project entails an attempt to implement a Generative Adversarial Network (GAN) architecture for converting black and white images to color images. The project was developed and trained within a Kaggle Jupyter notebook environment.

#### About the Project

The primary objective of this project is to explore the capabilities of GANs in the domain of image-to-image translation, specifically focusing on transforming grayscale images into colored counterparts. The architecture employed in this project consists of a U-Net generator coupled with a PatchGAN discriminator.

[Kaggle Notebook Link](https://www.kaggle.com/code/dobariyanaitik/pix2pix-gan-for-image-to-image-translation)

The U-Net generator is designed to capture high-level features while preserving spatial information, facilitating accurate colorization of grayscale images. Concurrently, the PatchGAN discriminator evaluates the local image patches, enabling fine-grained discrimination between real and generated images.

#### Libraries Used

- matplotlib
- numpy
- glob
- tensorflow
- keras

#### Results

The Pix2Pix GAN model underwent training for 100 epochs, resulting in compelling outcomes. Below are samples showcasing the transformation of grayscale images into their corresponding colorized versions:

![__results___20_1](https://github.com/NaitikDobariya/GAN-to-convert-B-W-image-to-RGB/assets/113834773/cca85e24-fe94-48ed-882f-ca8cbf6b0430)

![__results___20_3](https://github.com/NaitikDobariya/GAN-to-convert-B-W-image-to-RGB/assets/113834773/535b0902-7f31-4430-922f-f35d48a7d7e4)

![__results___20_5](https://github.com/NaitikDobariya/GAN-to-convert-B-W-image-to-RGB/assets/113834773/7b55c76f-01ab-4900-86a3-b644f4d5fafb)

![__results___20_7](https://github.com/NaitikDobariya/GAN-to-convert-B-W-image-to-RGB/assets/113834773/bfec178f-9e7c-49ee-be7c-6d6a9ef0cfd0)


Suggestions, and improvements are welcome.
