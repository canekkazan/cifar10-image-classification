# cifar10-image-classification

Image classification project on the CIFAR-10 dataset which consists of 60000 32x32 colour images in 10 classes, 
with 6000 images per class. There are 50000 training images and 10000 test images. The classes are airplane, 
automobile, bird, cat, deer, dog, frog, horseship, truck.

The number of parameters in the model are as following:
Total params: 834,122
Trainable params: 834,122
Non-trainable params: 0

After 75 epochs, the model's loss: 0.6528 and the model's accuracy: 0.7846 on the train data.
And the model's loss: 0.7890 and the model's accuracy: 0.7439 on the test data.

Data augmentation is not applied. In case of increment of the number of epochs,
the accuracy might increase up to 0.85, and the loss might decrease significantly.


mce
