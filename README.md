# EMNIST_MNIST_Trasfer_learning

Tranfer learning from **MIST** to **EMNIST**. <br/>
I used a CNN with the architecture [shown](model.png), trained the network with the [NIST database](http://yann.lecun.com/exdb/mnist/). <br/>
I used Keras with tensorflow as backend with an enviroment set up with Anaconda of the versions tensorflow=1.8.0 and keras=2.1.6.<br/>.
As before, The data comes split in the .mat file [downloaded](https://www.nist.gov/itl/iad/image-group/emnist-dataset), where the training set has the address "file['dataset'][0,0][0][0][0][0]", the training labels file['dataset'][0,0][0][0][0][1], the test set "file['dataset'][0,0][1][0][0][0]" and its labels "file['dataset'][0,0][1][0][0][1]".<br />
The accuraccy obtained after 15 epoch with a batch size of 512 was 93.68%  

