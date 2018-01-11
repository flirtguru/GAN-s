# GAN-s

*GENERATIVE ADVERSARIAL NETWORKS*  are a special type of networks in which 2 neural networks compete with each other ie. GENERATOR and DISCRIMINATOR.
Generator tries to generate images given a random sample of noise,Discriminator compares the generated images with the real ones and tells the Generator where it lacks
so the Generator gets stronger over time similarly Discriminator also gets stronger over time and then they both start to compete each other.


## Architecture of GAN's
![gans](https://user-images.githubusercontent.com/30948709/34805214-ed1af624-f6a2-11e7-8c51-767e00eb423a.jpeg)



### This code generated a MNIST sample as shown below:
![fake_samples_epoch_003](https://user-images.githubusercontent.com/30948709/34805156-92abee46-f6a2-11e7-8e5c-f7f277a1de92.png)


#####  This quality of generation can be improved by training more (lol).

## Dependencies 

Pytorch

## Advice 

Use GPU
