covers the functionality of various operations for the ROCm execution provider in the ONNX Runtime project. It includes typed kernel classes for operations such as GridSample, FastGelu, Gelu, BiasGelu, BiasSplitGelu, BiasAdd, QuickGelu, TransposeMatMul, FusedMatMul, Rfft, Irfft, ComplexMul, ComplexMulConj, BiasSoftmax, and BiasDropout. These kernel classes are used to execute these operations on ROCm devices. The code interacts with other parts of the project by utilizing shared libraries, the ROCm common functionality, and the provider API.

Interaction with other functional areas:
The code interacts with other parts of the project by inheriting from the base convolution class and utilizing functions and types from the ONNX Runtime ROCm provider. It also includes interactions with other files in the project for data processing, computation, and optimization. Additionally, it relies on the Composable Kernel framework, the TensorRT library, and the ROCm execution provider in ONNX Runtime.