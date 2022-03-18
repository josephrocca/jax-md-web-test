# JAX-MD Web Test
Running [JAX-MD](https://github.com/google/jax-md) molecular dynamics / particle simulation in the browser

## Demos:
* Minimal tflite (**not working** - [issue](https://github.com/tensorflow/tfjs/issues/6242)): https://josephrocca.github.io/jax-md-web-test/minimal/tflite.html
* Minimal ONNX - awaiting tf2onnx support for PartitionedCall op ([issue](https://github.com/onnx/tensorflow-onnx/issues/1864)). [Here's the conversion notebook](https://colab.research.google.com/drive/1NqJ2DZXAVTyoyJ4nlhp3i-_QpEJtBA7m).

## Notes:
* [Here's the conversion notebook](https://colab.research.google.com/drive/1o2BK1pukQd_u7GBTepLef4TKVubzKuYy) that goes from JAX to tflite via jax2tf and tf
