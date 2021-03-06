# net2vec

This repository is a collection of machine learning models for computer networks.

## mpnn

Extended results and code explanation supporting paper *Message-Passing Neural Networks Learn Little's Law* by Krzysztof Rusek and Piotr Chołda are avalable at in the notebook  [LittlesLaw](jupyter_notebooks/LittlesLaw.ipynb).
In [mpnn](mpnn) we provide a TensorFlow implementation of neural message passing architecture described in the paper.


**If you decide to apply the concepts presented or base on the provided code, please do refer our paper: K. Rusek and P. Chołda, "Message-Passing Neural Networks Learn Little’s Law," in IEEE Communications Letters. doi: 10.1109/LCOMM.2018.2886259.**

```
@ARTICLE{8572801, 
author={K. Rusek and P. Chołda}, 
journal={IEEE Communications Letters}, 
title={Message-Passing Neural Networks Learn Little’s Law}, 
year={2018}, 
volume={}, 
number={}, 
pages={1-1}, 
keywords={Delays;Neural networks;Topology;Routing;Network topology;Tools;Machine learning;Knowledge plane;machine learning;message-passing neural networks (MPNN);queuing networks;random graphs}, 
doi={10.1109/LCOMM.2018.2886259}, 
ISSN={1089-7798}, 
month={},}
```

## routenet

RouteNet is a neural architecture for network performance evaluation first proposed in the paper *Unveiling the potential of GNN for network modeling and optimization in SDN* by K. Rusek, J. Suárez-Varela, A. Mestres, P. Barlet-Ros, A. Cabellos-Aparicio accepted for ACM Symposium on SDN Research, April 2019, San Jose, CA, USA.

Imlementation is provided in  [routenet](routenet). 
