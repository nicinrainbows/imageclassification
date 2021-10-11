# imageclassification
Image classification of the STL-10 dataset with Inception ResNet V2 model with its classification head layer replaced by a squeeze-excitation block and customised dense, global average pooling and dropout layers.

The squeeze-excitation was adapted from https://github.com/titu1994/keras-squeeze-excite-network

Rest of the model was implemented using tensorflow-keras' API.

Training and validation accuracy was up to 96% without many signs of overfitting. Testing accuracy was consistently hitting approx 94.4%.
