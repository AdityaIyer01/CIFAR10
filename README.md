# CIFAR-10 Image Classification Using CNNs
`COMP 562 Spring 2022 Final Project`

Authors: Mohammed Alnasser, Daqi (Jen) Chen, Aditya Iyer, Rebecca Rozansky

## Abstract

Image analysis and classification are at the forefront of machine learning research. Our daily lives already make use of advanced image processing models, whether they be for identifying road signs for an autonomous vehicle or classifying malignant tumors. CIFAR-10 is a collection of low-resolution images that fall into ten different classes. In this paper, we construct a deep learning model consisting of convolutional and fully-connect layers to accurately classify each image.

## What does each model do?

### [Baseline Model](Baseline_Model.ipynb)

The baseline model consists of 3 VGG blocks.

### [Regularized Model](Regularized_Model.ipynb)

The regularized model is similar to the baseline model, but it contains a dropout layer after each VGG block and dense layer.

### [Regularized Model with Data Augmentation](Model_with_Data_Augmentation.ipynb)

The neural network architecture of this model is identical to that of the regularized model. However, the CIFAR-10 data is transformed before being fed into the model.

### [Regularized Model with Data Augmentation and Batch Normalization](Model_with_Batch_Normalization.ipynb)

This model is similar to the regularized model with data augmentation. However, the model contains a batch normalization layer after each convolutional layer and dense layer.

### [Final Model](Final_Model.ipynb)

The architecture of the final model is identical to that of the regularized model with data augmentation and batch normalization. However, the final model is trained over the entire, unpartitioned training set and evaluated on the test set. It achieves a test accuracy of 89.6%.

### [Visualizations](Visualizations.ipynb)

The notebook, <a href="Visualizations.ipynb">Visualizations.ipynb</a>, contains all of the graphs found in the <a href="Report.pdf">report</a> as well as a summary and diagram of each distinct neural network architecture.
