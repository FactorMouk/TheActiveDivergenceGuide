# Novelty search over learned representations

The article [Active Divergence with Generative Deep Learning - A Survey and Taxonomy](https://arxiv.org/abs/2107.05599) defines these methods in this way:

> Methods in this category take existing generative models
trained using standard maximum likelihood regimes and
then specifically search for the subset of learned representations that do not resemble the training data by systematically sampling from the model.

If we consider the distribution P as the training set and the distribution P' as the generated set, we are able to access a subset U that is not contained in P and is contained in P'. This set represents the artifacts generated with the furthest distance from the P set.

![noveltysearchimageoverlearned](https://drive.google.com/uc?export=view&id=1-JP-YANLP3KV-xlXoV8exxIT7ejEDMck)