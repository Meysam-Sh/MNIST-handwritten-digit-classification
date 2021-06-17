In this project, I've compared the performance of different ML algorithms for MNIST handwritten digit classification (http://yann.lecun.com/exdb/mnist/). The dataset consists of 60,000 small square 28×28 pixel images of handwritten single digits between 0 and 9. The task is to classify a given image of a handwritten digit into one of 10 classes. I implemented KNN, NN, RF algorithms using the sci-kitearn framework in Python. Then I tuned the hyperparameters of these algorithms to see which works better for this classification problem. In KNN, K, the number of neighbors, is the only parameter I tweaked. In NN, I tweaked several parameters of the algorithm, such as the number of layers, the number of neurons, the activation function, the learning rate. For the RF, the number of features to consider when looking for the best split, and the number of trees in the forest. And then I calculated the accuracy of the algorithms, it turned out that all algorithms achieved more than 90% accuracy, but, NN performed the best by achieving 99% accuracy.
