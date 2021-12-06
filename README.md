# PSoC&trade; 6 MCU: TinyML Hello World Example

This example is designed to demonstrate the absolute basics of using [TensorFlow
Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers).
It includes the full end-to-end workflow of training a model, converting it for
use with TensorFlow Lite for Microcontrollers for running inference on a
microcontroller.

- Code from https://github.com/tensorflow/tflite-micro/tree/main/tensorflow/lite/micro/examples/hello_world
- The folder tflm-cmsis was generated following the steps at https://github.com/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/new_platform_support.md#step-5-integrating-optimized-kernel-implementations
- Additionally in the Makefile, CMSIS_NN needs to be defined.
- Finally ModusToolbox only considers .cpp as C++ source code
- Run the following in the base folder
   find . -name "*.cc" -exec rename .cc .cpp {} +


## Document history

| Version | Description of change |
| ------- | --------------------- |
| 1.0.0   | New code example      |
