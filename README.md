# Fine tuning of vgg_faces for face sentiments analysis
[Based on the guide of Deshna Desai](https://deshanadesai.github.io/notes/Finetuning-VGG-For-Regression)
My intention is to fine tune VGGFaces model from the Caffe framework and using Nvidia Digits. My objective is to recognize face sentiments 6 sentiments + neutral one so it will classify 7 labels. 
## Preparing prototx
The prototxt file defines the architecture of the model on the case of the architecture and trained model provided by the [original authors Visual Geometry Group ](http://www.robots.ox.ac.uk/~vgg/software/vgg_face/)of University of Oxford don't provide prototxt for training and validating and obviously we will have to change the final output layers for working with our own labels.

