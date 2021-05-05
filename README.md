# Alexnet-Ciphar10
* see project.ipynb for code
* see report.pdf for final results.


Used the Alexnet pretrained model from pytorch to classify the images in the ciphar-10 dataset.
A confusion matrix was created that relates the CIFAR10 classes with the 10 most frequent classes from ImageNet predicted by the model.
![image](https://user-images.githubusercontent.com/43900229/117089932-e8bc1400-ad24-11eb-8987-677e861cc826.png)

Trained a linear classifier on the output features of the fc6 and fc7 layers.
