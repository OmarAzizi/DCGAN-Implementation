# DCGAN-Implementation
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

DCGAN is one of the popular and successful network designs for GAN. It's mainly composed of convolution layers without max pooling or fully connected layers. It uses convolutional stride and transposed convolution for the downsampling and the upsampling. The figure below is the network design for the generator.

![image](https://github.com/OmarAzizi/DCGAN-Implementation/assets/110500643/a0db5ab4-0180-4e62-b8a2-564456d5efe6)

After adding the Discriminator we will have a network that roughly looks like this:

![image](https://github.com/OmarAzizi/DCGAN-Implementation/assets/110500643/a21d5525-38c2-4cc5-80db-b41b5053cba4)

### Performance
This is a short video for the model running for 5 epochs.

[DCGAN Demo](https://www.youtube.com/watch?v=G1UeXhaDzTM)
