# Binary Image-Classification using pretrained convolutional Network 
In this project, we classify images based on taste. First, we extract embeddings using a pretrained convolutional neural network. Then, we build our own neural network for binary classification, which takes these embeddings as input and determines whether dish A tastes more like dish B (0) or dish C (1). This neural network consists of two linear layers and employs batch normalization, with ReLU and Sigmoid as activation functions. The network is optimized using Binary Cross Entropy Loss and the Adam optimizer. <br>
<br>
Please refer to `main.ipynb` for further details. 
