# Comparsion of TensorFlow Wrappers

## Speed of MLP

run Keras, TensorLayer and Tflearn with same model and data on a same GPU machine.

GPU: GTX980

Data: MNIST  train:50k  val:10k  test:10k

Model: 784-800-800-10

Num of epochs: 200

Batch size: 500

Keras: 282.475250s  = 1.41 s/epoch

TensorLayer: 116.670947s = 0.58 s/epoch

Tflearn:
