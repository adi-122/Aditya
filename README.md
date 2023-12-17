# Aditya
Forecasting of rose leaf disease (Quantification) as soon it appears on rose leaves.
Automatic detection of rose leaf disease detection and classification.
Increase accuracies Using large dataset to train the Algorithm and maximize epoch values.
Make use of existing deep learning models for rose leaf disease detection and will check their performance on the basis of various evaluation.

Initially, various architectures were analyzed, and then CNN was selected for the training of the model
because of the following reasons:
18/11/2023
●CNN is capable of self-learning the features of the dataset without human input.
●Ease of access to develop an image-based model, unlike other architecture.
●It can check multiple attributes of an input.
●It has comparatively more accuracy than single tool attribute checking.

Pre-Processing
After acquiring, the dataset is subjected to pre-processing such as resizing, image augmentation, etc. For
training with CNN, more number of images are needed. Hence data augmentation is used in this proposed
work. It is a method used to artificially boom the magnitude of a training dataset by making altered type of
images. It is used to improve the training dataset so that it will enhance the capacity of learning to generalize
and perform. It can favor CNN algorithms to learn the features that are at different location in an image.

Training and Testing
To develop a model for disease detection in rose plant leaves, the dataset is divided into 3 groups for training,
validation and testing. After splitting, the dataset are given to the CNN architecture for training. The CNN architecture
for disease detection in rose plant leaves is shown in previous slide. Rectified Linear activation function (ReLU) which
is most commonly used function was utilised to train the deep learning network.

Training Set
This set contains images that were captured under suitable circumstances of defective leaves. In the process, photos
show one leaf selected from the field and placed on a unique background under suitable environmental conditions. An
80% of the data randomly selected from an augmented dataset has been used for training the model. The training was
done for 50 epochs, mini batch size of 8, initial learning rate of 0.001 and optimized with stochastic gradient descent
algorithm.
Validation Set
The training set is evaluated with tuning parameters. Based on number of trials the tuning parameters were
finalised. For instance, to select the quantity of concealed units in a neural network. 10% of the data is used for
validation.
Test Set
The trained data set is evaluated without bias in the test set. About 10% of the data was used as the test data to
check the model. The test data is an unobserved data i.e., untrained by the architecture. The generalization ability
of the architecture is tested using this untrained data.

Training Accuracy and Validation Accuracy
Training accuracy indicates the ability of the model to classify
images during training of the model. The following graph
shows the training and validation accuracy plotted for every
epoch.
The reason for training accuracy is greater than validation
accuracy is that the data in the training set has been previously
trained to the model whereas the data in the validation set is
new for the model.
Because of this, model can be called as an over-fitting model.
An over-fitting model performs really well in training set but the
performance drops in validation set.

In this proposed work, a deep learning based CNN architecture was used to identify three types of diseases
namely Rose rust, Rose sawfly, Rose slug in rose plant leaves.
The accuracy of the model can be increased by increasing the quantity of images to train the model and the number
of epochs used. But it is not recommended to increase the number of epochs in greater numbers as it will increase
the time taken to execute architecture.
The suggested pesticide will also be displayed along with the disease.
So, an ideal and an effective way to increase the accuracy of the model are to increase the input images in the
dataset.
