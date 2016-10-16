# DLV


Note: the project is currently under active development. Please feel free to contact the developer. 

(1) Installation: 

To run the program, you need to install the following packages: 

Python 2.7
Theano
Keras

Moreover, to run experiments on ImageNet, one needs to download the VGG16 pre-trained model from 

https://gist.github.com/baraldilorenzo/07d7802847aaad0a35d3

and download images and put into the directory networks/imageNet/, and change the corresponding paths in networks/imageNet_network.py

(2) Usage: 

Use the following command to call the program: 

           python main.py

To run program for imageNet properly, one needs to include the directories 'caffe_ilsvrc12' and 'ImageNet_Utils' into scripts/networks/imageNet/ directory. Otherwise, the program cannot find images to process. 

Please use the file ''configuration.py'' to set the parameters for the system to run. More instructions on how to adapt the parameters will come later. 

