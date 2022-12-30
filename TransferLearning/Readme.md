Used VGG16 Net to train 3 models to classify if given image is cat or dog using Transfer Learning.

# Transfer Learning
<!-- What is Transfer Learning -->
Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task. The model developed for the first task is called the source model, and the model developed for the second task is called the target model. The source model is often trained on a large dataset, and the target model is often trained on a smaller dataset. The source model is used as a starting point for the target model because it has already learned a good representation of the input space. The target model is trained to learn a good representation of the target task.

# VGG16 Net
## **Description of VGG16 Net**
<!-- What is VGG net -->
VGG16 net is a convolutional neural network architecture. It is a 16-layer network that is 16 weight layers deep. This means that it has 16 weight layers that are stacked on top of each other. Each layer uses a **3x3 convolutional** filter (with stride=1 and padding=same) that is followed by a rectified linear unit (ReLU) and a **2x2 max-pooling** (stride=2) operation. The stack of convolution layer is followed by three fully connected layers where the first two has 4096 units each with **Relu** activation and the third has 1000 **Softmax** units. The architecture of the network is shown below.

## **VGG16 Net Architecture**
<!-- VGG16 Architecture -->

# Steps to train the model using Transfer Learning
<!-- Steps to train the model using Transfer Learning -->
1. Load a pre-trained VGG16 model built into Keras.
2. Remove the last three fully connected layer of the model.
3. Freeze the weights of the remaining layers.
4. Add layers to the model to make it suitable for the new task.
5. Train the model on the new dataset.
6. Test the model on the new dataset.













