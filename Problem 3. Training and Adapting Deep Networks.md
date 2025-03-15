**REMINDER:** Problem 3 applies content covered in [Week 4](https://canvas.qut.edu.au/courses/20364/modules/276458 "Week 4 - Introduction to Deep Learning") and [Week 5](https://canvas.qut.edu.au/courses/20364/modules/276459 "Week 5 - Deep Learning").

---

When training deep neural networks, the availability of data is a frequent challenge. As such, methods including fine tuning and data augmentation are common practices to address data challenges.

You have been provided with three portions of data from the Street View House Numbers (SVHN) dataset, a ‘real world’ MNIST style dataset. The three data portions are:

1. A training set, Q3/q3 train.mat, containing 1, 000 samples distributed across the 10 classes.
2. A validation set, Q3/q3 validation.mat, containing 1, 000 samples distributed across the 10 classes.
3. A testing set, Q3/q3 test.mat, 10, 000 samples distributed across the 10 classes.

Data sets do no overlap, and have been extracted randomly from the original SVHN test set. Note that the training set being significantly smaller than the test set is by design, and is not an error. The provided template code implements an SVM to classify this data, and  
provides code to time how long the SVM takes during training and testing

---

#### Using this data

Using these datasets and the provided code, you are to:

1. Design/select a DCNN architecture, and using this network:
    1. Train a model from scratch, using no data augmentation, on the provided abridged SVHN training set.
    2. Train a model from scratch, using the data augmentation of your choice, on the provided abridged SVHN training set.
2. Compare the performance of two DCNNs (with and without augmentation), considering the accuracy, training time and inference time (i.e. time taken to evaluate the  
    models), using the provided test set.

All models should be evaluated on the provided SVHN test set, and their performance should be compared. DCNN architectures may be taken from lecture examples or practical solutions. Your selection of model may take computational constraints into consideration.

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| For problem 3, your response must include sections that address the following:<br><br>- Discussion of neural network design (i.e. the network topology), and training approach. Discussion of training should include details of how long the network was trained for, and if training converged. If the design was constrained due to limited computational resources, this should be clearly stated.  <br>    **(suggested length, 2/3 page excluding figures/tables)**<br>- Discussion of the data augmentations used, including a brief justification as to why these were chosen.  <br>    **(suggested length, 1/3 page excluding figures/tables)**<br>- Comparison between the two DCNNs (with and without augmentation) and the SVM which considers both performance, training time, and inference time. Evaluation should us appropriate metrics and/or visualisations to highlight any differences in performance between the models.  <br>    **(suggested length, 1 page excluding figures/tables)** |
