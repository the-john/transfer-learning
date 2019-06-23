# Transfer Learning

In this git repository I have sample code that I intend to cut/past/modify for future projects.

There are a LOT of very good models out there, many of which had tons of compute time invested in them to get them trained.  We can utilize some of that goodness by reusing these models for our own purposes.

The idea is to take a well functioning model, modify it slightly to fit your needs, and retrain the parts that you modified.  This can yield an impressive model in a fraction of the time and effort.

With this sample code, you can see how I used the (VGGNet)[https://arxiv.org/pdf/1409.1556.pdf] model that was trained on the (ImageNet dataset)[http://www.image-net.org/].  This model classifies 1,000 different objects in an image.

A popular thing to do is to just change the last model layer, the Fully Connected (FC) layer, to represent whatever it is that you want to classify.  Retrain with your own data (just the layers that you changed), and HOTDOG ... you gotta awesome capability.

For more details, please refer to (CS231 Stanford Course Notes)[http://cs231n.github.io/transfer-learning/].

Specifically, I use the VGGNet to identify pictures of flowers.  A sample of the training data is below.

![]()
