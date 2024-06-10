# luke_gpt
Simple generatively pretrained transformer based off the paper "Attention is All You Need"  

Followed tutorial by Andrej Karpathy

GPT trained on Shakespeare

# Notes and things I learned
<img src="assets/transformer.png">

* Tensors in the PyTorch lib are specialized data structures that are similar to arrays and matrices.  These are used to encode the inputs and outputs of a model along with the model's parameters.

* We train NN (Neural Networks) using the encoded data chunks at a time, not all at once.  This is known as block size or context length.  You can see this in Code Cell 10. 

* The steps to training your NN: Data preparation, model initialization, loss functions, optimizer, training loop, validation and then saving and testing the model.

* What is self attention?: mechanism within neural network models, particularly in the context of natural language processing (NLP) and sequence modeling, that allows the model to focus on different parts of the input sequence when producing an output. This mechanism is a key component of the Transformer architecture, which has become the foundation for many state-of-the-art models, such as GPT.