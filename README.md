# Alexnet-Ciphar10
* see report.pdf for final results.


Used the Alexnet pretrained model from pytorch to classify the images in the ciphar-10 dataset.
A confusion matrix was created that relates the CIFAR10 classes with the 10 most frequent classes from ImageNet predicted by the model.
Trained a linear classifier on the output features of the fc6 and fc7 layers.
