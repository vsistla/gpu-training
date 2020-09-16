# Gpu-training

This repo is built using minGPT (https://github.com/karpathy/minGPT). 
This is used a baseline to discuss some of the challenges of GPU training and how to be aware of memory issues and plan accordingly during your training phases of your NLP models. These memory suggestions are not limited to NLP - for any kind of AI problem. 

This is used as a demo file for Global AI/Big Data Conference presentation - on Sept 16th 2020 - to discuss some of the aspects of GPU training of NLP models using PyTorch.

### So, I will use this code base to "train" a min GPT model BUT please note that I will not able to complete the training - as each such training will take upwards of 15 mins and I only 30 mins to do this demo. So, I will keep starting and stopping the training to demonstrates aspect you all need to be aware of when doing GPU training.

### Also, I only discuss play_char.ipynb - which trains a GPT to be a character-level language model on arbitrary text, similar to Karpathy's older char-rnn but with a transformer instead of an RNN

### Since minGPT uses PyTorch, all my commands and examples are limited to PyTorch and may or may not apply to other libraries such as TensorFlow, Keras, etc.


# Agenda

> 1. Background & Expectations
> 2. Quick overview of the GPU platform I am using for the demo - trainml.ai
> 3. Hyperparameters & Training
> 4. Options to check while the model is training
> 5. Memory management
> 6. Some experimental data
> 7. Final Thoughts
> 8. Trainml.ai Platform overview
> 9. Offer for demo attendees
