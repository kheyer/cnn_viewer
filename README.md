# cnn_viewer

This tool is designed to save activations from a convolutional neural net trained in [fast.ai](https://github.com/fastai/fastai).
Activations can be saved as individual images, composite images (all activations in a given layer) or as an animation.

At a minimum the tool requires a `model` and the `PATH` and `filename` for the image that will be fed into the model. Other parameters 
control how the input image is resized and the sizes of the output images/animations.

cnn_viewer.py should work with any fast.ai convolutional model that works with three channel images.

Some examples of activation images:

![Layer0](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer0_image0.jpg)
![Layer1](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer1_image4.jpg)
![Layer2](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer2_image11.jpg)
![Layer3](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer3_image11.jpg)
![Layer4](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer4_image11.jpg)
![Layer5](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer5_image1.jpg)
![Layer6](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer6_image8.jpg)
![Layer7](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer7_image6.jpg)
![Layer8](https://github.com/kheyer/cnn_viewer/blob/master/individuals_example/layer8_image11.jpg)
![Composite4](https://github.com/kheyer/cnn_viewer/blob/master/composite_example/layer4.jpg)
