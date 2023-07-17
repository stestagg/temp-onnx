covers the functionality of building and managing quantized neural network (QNN) models in the ONNX Runtime project. It includes functions and classes for setting properties of QNN tensors, managing the QNN backend, composing and managing the graph information of a QNN model, providing utility functions and operators for QNN operations, creating and managing QNN graphs, registering and creating op builders for various operations, and building operators for QNN models.

Interactions with other functional areas:
- The code interacts with the QNN_Tensor_t structure and other components of the ONNX Runtime project for handling quantized neural network operations.
- It interacts with QNN-specific headers, resolves symbols, and logs information for managing the QNN backend.
- It includes headers from the same directory and other directories to import necessary dependencies for the QnnModel class.
- It interacts with the GraphViewer class, Node class, GraphInfo class, OnnxTensorInfo class, OpBuilderFactory class, and logger to obtain and process graph information, input/output definitions, and build operators for the quantized model.
- It interacts with the QNN interface, tensor wrappers, and parameter wrappers for creating and managing a QNN graph in the QnnModelWrapper class.
- It interacts with the BaseOpBuilder class, QnnModelWrapper class, logging utilities, and other op builders in the opbuilder subdirectory for building various operators for QNN models.