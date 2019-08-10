# Recreating The Simpsons with GANs
Inspired by my progress (and mammoth failures) of my previous deep convolutional generative adversarial network for image synthesis of basketball shoes, I wanted to test the learning capabilities of the neural network I built against another domain, which was equal parts accessible and fun: The Simpsons. The data presents a neat set of computer vision challenges due to image format and structure, and is also easier to evaluate since we're all so familiar with Springfield's beloved residents. As images are generated, we can visually see the progression and developing accuracy of learning character compositions, pick apart inconsistencies, and see when the system breaks down and is in need of tuning.

I'll be adding more flavors & architectures of GANs as this repo progresses to (hopefully) achieve more convincing results. 

- [Grab the data](https://www.kaggle.com/kostastokis/simpsons-faces)
- [Read the notes](https://medium.com/@jasonsalas_89883/recreating-the-simpsons-with-a-dcgan-2122f788faea)

# Output images
Here's the output after a simple model with a 40,000-iteration training run

![model training](https://github.com/jasonsalas/simpsons_gan/blob/master/crossfade_40000_training_run.gif)

...more training with a deeper, more complex model starts to produce better results...
![more model training](https://github.com/jasonsalas/simpsons_gan/blob/master/training_by_epoch.gif)

...the deepest model produces smooth edges, reduces pixelation and captures fine details.
![after 80 epochs of deep training](https://github.com/jasonsalas/simpsons_gan/blob/master/3.png)
