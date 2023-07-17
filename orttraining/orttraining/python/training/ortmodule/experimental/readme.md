the experimental functionality of the ONNX Runtime Training project. It defines the package structure and provides necessary imports for the experimental features. It includes the HierarchicalORTModule class, which allows wrapping submodules of a PyTorch module as ORTModules. The code also handles loading and applying configuration data from a JSON file to an ORTModule object. 

Interactions:
- The code imports and exposes experimental features and functionalities to other files, classes, and components within the project.
- It imports and uses classes and functions from the ortmodule, ORtModule, and debug_options modules for the HierarchicalORTModule class.
- It imports modules and classes from various packages to access and modify the configuration of the ORTModule in the json_config directory.