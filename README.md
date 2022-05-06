# CIFAR-10 Image Classification Using CNN
`COMP 562 Final Group Project`

Authors: Aditya Iyer, Rebecca Rozansky, Daqi (Jen) Chen, Mohammed Alnasser

## About the Repository

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

## Final Project Report Guidelines
Your final project report can be at most four pages long (include all text, appendices, figures, and anything else), with one additional page that can contain nothing but references, and must be written in LATEX. If you did this work in collaboration with someone else, or if someone else (such as another professor) had advised you on this work, your report must fully acknowledge their contributions. At a minimum, your final report must describe the **problem/application and motivation, survey related work, discuss your approach, and explain your results/conclusions/impact of your project**. 

It should include enough detail such that someone else can reproduce your method and results. You are also required to provide a link to a `GitHub repository` where your code is stored. 

You may look at previous projects or papers from the list in section 2 to get an idea of what should be included in your project report. 

You will likely end up with a better report if you start by writing a 6-7 page report and
then edit it down to 4 pages of well-written and concise prose. Keep in mind if you have an exciting and novel
idea for this project, you can extend your work and submit it to an appropriate machine learning conference.

## Final submission instructions

Save your report as a PDF file of 5 pages or less. Again, The corresponding member of the team should submit
the final PDF and the GitHub link through Sakai by the announced deadline.
