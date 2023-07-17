covers functionality related to the provider host in the ONNX Runtime project. It defines a global variable and provides functions to get and set the provider host. This code interacts with other parts of the project by allowing access to the provider host through the global variable. Other components or files can call the provided functions to retrieve or set the provider host and perform operations or access resources provided by the host.

Directory: ./node_unit

Summary:
The code in this directory covers functionality related to quantized linear operations (QLinearOps) in the ONNX Runtime project. It includes functions to determine the type of QLinearOp, check if an operation is unary, binary, or variadic, and retrieve input or output nodes and definitions for a given QDQ (Quantize-Dequantize) NodeGroup. This code interacts with other parts of the project such as the graph viewer, optimizer, and shared utility functions.

Directory: ./utils

Summary:
The code in this directory provides utility functions and classes for the ONNX Runtime project. It includes functions for getting the type and clip min/max values of a node, as well as a helper class for accessing node attributes. This code interacts with other parts of the project by including headers from various modules and using classes and functions from these modules to perform its tasks. It interacts with modules such as common, framework, graph, providers, optimizer, and initializer.