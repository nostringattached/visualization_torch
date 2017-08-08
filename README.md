## Visualization toolbox for torch

A rewrite of CNN visualization example from ["Lasagne"](https://github.com/Lasagne/Recipes/blob/master/examples/Saliency%20Maps%20and%20Guided%20Backpropagation.ipynb) and ["PyTorch"](https://github.com/leelabcnbc/cnnvis-pytorch/blob/master/test.ipynb) in torch.

They did exactly the same thing. However, the results are not exactly the same. 

### Requirements
- Install Torch with CUDA GPU. Install the basic packages (nn, optim, image, cutorch, cunn).
- [cudnn](https://developer.nvidia.com/cudnn) and [torch bindings](https://github.com/soumith/cudnn.torch).
- [loadcaffe](https://github.com/szagoruyko/loadcaffe)
