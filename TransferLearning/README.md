# Transfer Learning
 
The repository shows how to use Transfer Learning. 

In the noteboook, we used [VGGNet](https://arxiv.org/pdf/1409.1556.pdf) trained on the [ImageNet dataset](http://www.image-net.org/) as a feature extractor. Below is the architecture of the VGGNet with a series of convolutional and maxpooling layers, then three fully-connected layers at the end that classify the 1000 classes found in the ImageNet database. 

<img src="https://github.com/Shahrullo/DeepLearningPytorch/blob/main/TransferLearning/notebook_ims/vgg_16_architecture.png">

VGGNet is great because it's simple and has great performance. The idea here is that we keep all the convolutional layers, but replace the final fully-connected layer with our own classifier. This way we can use VGGNet as a fixed feature extractor for our images then easily train a simple classifier on top of that.

* Use all but the last fully-connected layer as a fixed feature extractor.
* Define a new, final classification layer and apply it to a task of our choice!

If you want to know more information about `transfer learning`, [this link](https://cs231n.github.io/transfer-learning/) will be helpful
