# Classification of numerical data characteristics

In this project, a method to classify the chracteristics of a series of numerical data values is implemented as neural network in keras (on Tensorflow backend).

## Training Dataset

The NN was trained with three classes of charactateristics - in this case the equations of parabola, circle an a straight line. All available parameters in these equations are being feed with random values within a predefined range. The script "curve_dataset_generator.ipynb" calculates 1000 training/validation samples and 10 test samples of each equation type.

(image)

## Notes for usage and adaption

Please note that the input shape of this example is (1,20).
This means, the input data is limited to 10 sample points. They have to be in the order (x1, y1, x2, y2, xn, yn, ...).
If you want to feed more sample points to the network, you will have to change the input shape in the implementation. You may also have to add more layers and/or modify the depth of the Dense layers.
