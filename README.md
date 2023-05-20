# CNN-Architecture
History and Updates
- In this article, we will focus on the evolution of convolutional neural networks (CNN) architectures.
- If we plot the accuracy of all the reported works on Imagenet, we would get something like this:

![image-classification-plot-imagenet](https://github.com/Er-Divyesh-Sethiya/CNN-Architecture/assets/103837830/bed23176-ec48-44b1-b305-a0084c1bd0c7)

To provide another visual overview, one could capture top-performing CNNs until 2018 in a single image:

![deep-learning-architectures-plot-2018](https://github.com/Er-Divyesh-Sethiya/CNN-Architecture/assets/103837830/c293e227-4362-432a-8170-ce6ca1d80937)

- Note that, the FLoating point Operations Per second (FLOPs) indicate the complexity of the model, while on the vertical axis we have the Imagenet accuracy. The radius of the circle indicates the number of parameters.

# Fully Convolutional Network (FCN)

- Fully convolutional network 1 was one of the first architectures without fully connected layers. Apart from the fact that it can be trained end-to-end, for individual pixel prediction (e.g semantic segmentation), it can process arbitrary-sized inputs. It is a general architecture that effectively uses transposed convolutions as a trainable upsampling method.

![fcn-architecture](https://github.com/Er-Divyesh-Sethiya/CNN-Architecture/assets/103837830/440176a9-8d2c-41f6-8759-86f49b7c3f3a)
