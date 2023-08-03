contains code related to attention mechanisms and LSTM operations in the project. It includes implementations of the AttentionWrapper class, which processes RNN cell outputs and applies attention mechanisms, and the Bahdanau Attention mechanism, which calculates attention weights and context vectors. The directory also includes the AttnLSTM operator for the Deep CPU execution provider, which computes LSTM operations with attention, and the UniDirectionalAttnLstm class, which performs computations for a unidirectional LSTM with attention. These files handle various aspects such as setting weights, initializing buffers, handling optional inputs, and parallelization of computations.