contains code related to the scheduling of tensors in the code generation process of the project. It includes files that implement the Softmax scheduler, evaluation rules for the TVM scheduler, and the TVMScheduleBuilder class for managing TVM schedules. The code in this directory handles the optimization of tensor scheduling, including the insertion of root schedules, closures, and input root schedules. The TVM scheduler is responsible for determining the execution order of operations in the code generation process based on different criteria.