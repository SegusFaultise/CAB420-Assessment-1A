**REMINDER:** Problem 2 uses content from [Week 3](https://canvas.qut.edu.au/courses/20364/modules/276457 "Week 3 - Classification").

---

Land use classification is an important task to understand our changing environment. One approach to this involves the use of data from aerial sensors that captures different spectral reflectance properties of the ground below. From this data, the land type can be classified.

You have been provided with training, validation and testing data (Q2/training.csv, Q2/validation.csv and Q2/testing.csv) that include 27 spectral properties and an overall classification of land type, which can be one of:

-  _s_ : ‘Sugi’ forest;
- _h_ : ‘Hinoki’ forest;
- _d_ : ‘Mixed deciduous’ forest;
- _o_ : ‘Other’ non-forest land

---

#### Using this data

Using the provided data as-is, you are to train three multi-class classifiers to classify land type from the spectral data. These classifiers are to be:

1. A K-Nearest Neighbours Classifier;
2. A Random Forest; and
3. An ensemble of Support Vector Machines.

Model hyper-parameters should be selected using a grid search operating over the validation set. The resultant models are to be evaluated on the testing set and compared.

|     | For problem 2, your response must include sections that address the following:<br><br>- Discussion and justification of any pre-processing performed, such as standardisation.  <br>    **(suggested length, 1/3 page excluding figures/tables)**<br>- Details of the hyper-parameter selection method, the final model parameters selected, and a discussion of these in relation to characteristics of the data. Discuss the effect of your hyper-parameters will have on the model (ie. if you have found a small value for a hyper parameter, what effect will this have on the model compared to a large value?)  <br>    **(suggested length, 2/3 page excluding figures/tables)**<br>- An evaluation and comparison of the final three models, including a discussion exploring any difference in performance between the models.  <br>    **(suggested length, 1 page excluding figures/tables).** |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |