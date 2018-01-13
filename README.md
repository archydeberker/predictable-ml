# predictable-ml

This repo contains some experiments inspired by [Baidu's recent paper](https://arxiv.org/abs/1712.00409)on predicting scaling of ML algorithms with 
increasin dataset size.

They found, somewhat surpisingly, that model performance grows with dataset size with a power-law relationship that 
seems remarkably consistent for a given task. Most surprisingly, this is invariant to architecture, which seems to shift
the intercept but not the slope of this relationship.

For discussion, see [the blogpost](http://research.baidu.com/deep-learning-scaling-predictable-empirically/) which accompanies the paper.

## To Do:

[] Implement simple CIFAR-based experiment to replicate central finding 

[] See whether a similar approach might be used to predict hyperparamter impact based upon small data sample


