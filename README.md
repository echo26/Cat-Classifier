# CatClassifier


Basic CNN predicting whether image is a cat or not using Tensorflow and Keras.


The image size is 64 * 64.

So, I made CNN of 32 nodes and 4*4 filter 3 times. Then, I made pool layer with pool-size(2,2). It will become Denser layer with 128 nodes using flattening layer. It becomes denser layer with 2 nodes and finally brings output with applied sigmond function.
