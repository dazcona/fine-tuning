# Transfer Learning: Fine-tuning Networks

Transfer learning: ability to use a pre-trained model as a "shortcut" to learn patterns from data it was not originally trained on.

There are two types of transfer learning in the context of deep learning:

1. Transfer learning via feature extraction
2. **Transfer learning via fine-tuning**: modify the architecture of a network so we can re-train parts of the network

This repo will focus on the second method of transfer learning

## Datasets

### Flowers-17

Pictures of 17 category flower dataset with 80 images for each class. [Dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/17/) was collected by the Visual Geometry Group at the University of Oxford.

![](docs/flowers17.jpg)

## Technologies

* [keras](https://keras.io)
* [tensorflow](https://www.tensorflow.org/)
* [scikit-learn](https://scikit-learn.org/)
  
## Deployment with Docker

1. Build the docker image:
```
$ cd docker
$ make build
```

2. Create a docker container based on the image:
```
$ make run
```

3. SSH to the docker container:
```
$ make dev
```

...

## Resources

* Deep Learning for Computer Vision with Python by Dr. Adrian Rosebrock: https://www.pyimagesearch.com/deep-learning-computer-vision-python-book/
