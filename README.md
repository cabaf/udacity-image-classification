## Cifar10 Image Classification Project.
In this project, we classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects. Here, we preprocessed the data, then train a convolutional neural network on all the samples. We normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, we inspect their predictions on the sample images.  

![Cifar10][image-cifar10]

## Installation
You only need to install [Conda](https://conda.io/docs/install/quick.html) and run the following commands:
```
conda env create -f ud-im-classification.yml
source activate ud-im-classification
```
You can open the solution by simply:
```
jupyter notebook dlnd_image_classification.ipynb 
```

<!-- Images -->
[image-cifar10]: https://msdnshared.blob.core.windows.net/media/2016/10/102816_2258_ApplyingClo2.png "Cifar10 Examples"
