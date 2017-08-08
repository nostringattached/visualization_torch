## Visualization toolbox for torch

A rewrite of CNN visualization example from [Lasagne](https://github.com/Lasagne/Recipes/blob/master/examples/Saliency%20Maps%20and%20Guided%20Backpropagation.ipynb) and [PyTorch](https://github.com/leelabcnbc/cnnvis-pytorch/blob/master/test.ipynb) in torch.

They did exactly the same thing. However, the results are not exactly the same. 

### Requirements
- Install Torch with CUDA GPU. Install the basic packages (nn, optim, image, cutorch, cunn).
- [cudnn](https://developer.nvidia.com/cudnn) and [torch bindings](https://github.com/soumith/cudnn.torch).
- [loadcaffe](https://github.com/szagoruyko/loadcaffe)

### Paper Included
[1]: Zeiler et al. (2013): [Visualizing and Understanding Convolutional Networks](http://arxiv.org/abs/1311.2901)
[2]: Simonyan et al. (2013): [Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps](http://arxiv.org/abs/1312.6034)
[3]: Springenberg et al. (2015): [Striving for Simplicity - The All Convolutional Net](http://arxiv.org/abs/1412.6806)
