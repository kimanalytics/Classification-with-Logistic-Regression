# Classification-with-Logistic-Regression

### Note: We've adapted this Mini Project from  Harvard's Lab 5 in the CS109 course.

### We turn our attention to classification. Classification tries to predict, which of a small set of classes, an observation belongs to. Mathematically, the aim is to find y, a label based on knowing a feature vector x. For instance, consider predicting gender from seeing a person's face, something we do fairly well as humans. To have a machine do this well, we would typically feed the machine a bunch of images of people which have been labelled "male" or "female" (the training set), and have it learn the gender of the person in the image from the labels and the features used to determine gender. Then, given a new photo, the trained algorithm returns us the gender of the person in the photo.

### There are different ways of making classifications. One idea is shown schematically in the image below, where we find a line that divides "things" of two different types in a 2-dimensional feature space. The classification show in the figure below is an example of a maximum-margin classifier where construct a decision boundary that is far as possible away from both classes of points. The fact that a line can be drawn to separate the two classes makes the problem linearly separable. Support Vector Machines (SVM) are an example of a maximum-margin classifier.
