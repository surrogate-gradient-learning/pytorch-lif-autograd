# Synaptic Plasticity Dynamics for Deep Continuous Local Learning (DECOLLE)

This repo contains a tutorial for the [PyTorch](https://pytorch.org/) implementation of the DECOLLE learning rule presented in [this paper](https://arxiv.org/abs/1811.10766).

If you use this code in a scientific publication, please include the following reference in your bibliography:

```
@article{kaiser2018synaptic,
  title={Synaptic Plasticity Dynamics for Deep Continuous Local Learning (DECOLLE)},
  author={Kaiser, Jacques and Mostafa, Hesham and Neftci, Emre},
  journal={arXiv preprint arXiv:1811.10766},
  year={2018}
}
```
## Tutorials

The first notebook under the tutorials is standalone except for snn_utils.py.
Step-by-step instructions for setting up spiking neural networks in PyTorch and setting up DECOLLE are provided. 
See for example [tutorial1.ipynb](tutorial1.ipynb).

## Google Colab
You can open the notebook in colab, but you will have to upload or clone snn_utils.py by yourself
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/surrogate-gradient-learning/pytorch-lif-autograd/blob/master/)
