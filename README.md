# CIFAR-10 Image Classification Using CNN
`COMP 562 Final Group Project`

Authors: Mohammed Alnasser, Daqi (Jen) Chen, Aditya Iyer, Rebecca Rozansky

## Abstract

Image analysis and classification are at the forefront of machine learning research. Our daily lives already make use of advanced image processing models, whether they be for identifying road signs for an autonomous vehicle or classifying malignant tumors. CIFAR-10 is a collection of low-resolution images that fall into ten different classes. In this paper, we construct a deep learning model consisting of convolutional and fully-connect layers to accurately classify each image.

## What does each model do?

### Baseline Model

The baseline model consists of 3 VGG blocks.

### Regularized Model

The regularized model is the same as the baseline model but with dropout layers implemented after each VGG block.

### Data Augmented Model

The data augmented model manipulates and transforms the data before it is fed into the neural network.

### Batch-Normalized Model

The batch-normalized model adds a batch-normalization layer after each layer in the network.

### Final Model

The final network combines all of the models above to produce our final accuracy of 89.6%.

### Visualizations

Generates all of the graphs we used in our reports as well as summaries and diagrams of each model.
