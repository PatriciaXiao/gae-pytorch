# gae-pytorch
Graph Auto-Encoder in PyTorch

This is a PyTorch implementation of the Variational Graph Auto-Encoder model described in the paper:
 
T. N. Kipf, M. Welling, [Variational Graph Auto-Encoders](https://arxiv.org/abs/1611.07308), NIPS Workshop on Bayesian Deep Learning (2016)

The code in this repo is based on or refers to https://github.com/tkipf/gae, https://github.com/tkipf/pygcn and https://github.com/vmasrani/gae_in_pytorch.

### Requirements
- python 3.7
- PyTorch latest version
- networkx

### How to run
```bash
python train.py
```
### in my case
```bash
python train.py -d my
```