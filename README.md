Udacity Deep Learning Nanodegree Project : Dog Breed Classifier Application using Pytorch

I build a pipeline to predict the breed of dog in a given realword image.

By building a CNN from scratch, we aim to understand the fundemantals concepts like gradient descent, backpropagation, etc. 
better before using Pytorch to implement and use more complex tools, concepts, models in the following modules of this Udacity
 program.

We used the data coming from both the UCI Machine Learning Database and our personal collections.

Given a set of images in a directory, final algorithm displays if any human or dog detected. If a human detected, it displays the resembling
dog breed for the human! If a dog detected, it gives the predicted breed and corresponding picture of the dog used in training of the model.

In the scratch version, I tried a simple version of original VGG16 mode, essentially by reducing and eliminating some layers from the model. 
For transfer learning version, I used pre-trained VGG16 Net to find the predicted breed (class) of a given picture.

To satisfy project rubrics, we aimed at least 10% accuracy on the test set for the scratch model and at least 60% accuracy on the test set for the transfer
learning model. So even though my epochs are insufficient, I tried to save my free GPU hours for the following projects! By adding more layers and using more epochs,
accuracy can be improved further beyond other tunings and configuration modifications.
