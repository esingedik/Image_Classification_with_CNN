# Image_Classification_with_CNN
Image Classification with CNN (Convolutional Neural Networks)

A CNN model was developed to find out which generic class a given image belongs to.

The process steps are:

1. For model training, pre-classified images in the CIFAR-10 data set can be used.
2. 80% of the data is allocated for training, and 20% is reserved for testing.
3. The input images in the CNN model are reshaped to 200x200 dimensions.
4. The transitions between the CNN layers are based on the formula _(W-K+2P)/S+1_.

The network structure is as follows.

![Alt text](https://user-images.githubusercontent.com/35924267/54076726-7aec3d00-42bf-11e9-991b-09c61ee04de5.png?raw=true "Network_Structure")

The accuracy of the model is *92.47%*.
