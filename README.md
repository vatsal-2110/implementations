# implementations
this repository contains implementations :
## 1) MLP for character level language model name prediction:
This is a MLP inspired by Andrej Karpathy's makemore second video, in which he built a MLP. This is a similar implemetation of that where i have tried some of the exercise mentioned in the description.

## 2) activations and batchnorm :
This is pytorchifying MLP along with several updates that make training neural networks easier like batch normilazation and it also have various tolls for activation and gradient inspection. This is inspired by Andrej Karpathy's makemore third video. it also has some experiments like zero init of weights and folding batchnorm layer weights into previous layer

## 3) backprop :
In this the pytorch's loss.backward() is removed and the backpropagation is implemented from scratch. it has forward as well as backward pass. This is inspired by Andrej Karpathy's makemore fourth video.

## 4) trigram_character_level_language_model :
This is a character-level model inspired by Andrej Karpathy's makemore first video, in which he implemented a bigram model. This is a modified version of that in which I have implemented a trigram model based on similar architecture

## 5) Wavenet model :
This is the implementation of wavenet model in pytorch. This is inspired by Andrej Karpathy's makemore fifth video. ot does not containn much experimentation, it just has wavenet implementation.

