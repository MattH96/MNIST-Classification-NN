# MNIST-Classification-NN
Two MNIST classification python notebooks, one using classical ML techniques and the other using a Keras neural network.

![Alt text](https://github.com/MattH96/MNIST-Classification-NN/blob/master/Images/MNISTData.png?raw=true "MNIST Images")

IMPORTANT NOTE: The MNIST dataset is large and so cannot be uploaded to this repo. you can download it here http://yann.lecun.com/exdb/mnist/  
Then simply change the #import file destination to make use of these note books.

MNIST Classification Notebook:
Goes through some classical techniques for classification, K-nearest-neighbours and random forest. Tests are run on the applicability of different values for K number of neighbours leading to the following accuracy results:

![Alt text](https://github.com/MattH96/MNIST-Classification-NN/blob/master/Images/MNIST%20KNN%20Acc.png?raw=true "KNN Accuracy")

Various dimensionality reduction techniques and which when tested with the optimal KNN results achieve these results:

![Alt text](https://github.com/MattH96/MNIST-Classification-NN/blob/master/Images/DimRed.png?raw=true "Dimensionality Reduction Accuracy")

MNIST Convolution Neural Network:
This covers the use of the Keras library for Neural Networks. I won't go into the details here but with fairly simple CNN implementation I achieved this confusion matrix at 98.8% Accuracy:

![Alt text](https://github.com/MattH96/MNIST-Classification-NN/blob/master/Images/CNNOutput.png?raw=true "CNN Output")

For further regularisation I implemented a data generating process which moves/distorts images in the dataset randomly, the model then achieved 99.1% accuracy with the following confusion matrix:

![Alt text](https://github.com/MattH96/MNIST-Classification-NN/blob/master/Images/DataGenCNN.png?raw=true "CNN with DataGen Output")

The ideology behind tests/implementation and results are more clearly seen in the notebooks so I reccomend you give it a look! 
