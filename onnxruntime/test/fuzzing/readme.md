contains code files related to unit testing, ONNX model prediction, mutation testing, and logging for the project. 

The "BetaDistribution.cpp" file includes functions for unit testing the BetaDistribution class and generating random data. It performs experiments using the BetaDistribution class to generate random numbers and displays a histogram of the distribution.

The "OnnxPrediction.cpp" file implements the OnnxPrediction class, responsible for loading an ONNX model into a session and running predictions using the model. It provides methods for initializing the model, generating input data, running inference, and printing the output values. The class utilizes the onnxruntime library for loading and running the model.

The "test.cpp" file contains the main code for a program that performs mutation testing on ONNX models. It takes an unmutated ONNX model as input, generates mutated versions of the model, runs predictions on the mutated models, and logs any exceptions or errors encountered during the process. It also offers options for verbose logging, stress testing, and saving the mutated models to files.

The "testlog.cpp" file implements a logging system for the project. It includes functions to insert log messages into a ring buffer, output log messages to the console, flush log messages to a log file, and handle line breaks in log messages. The file also includes a singleton constructor for initializing the logging system and a helper function for converting strings to wide strings.