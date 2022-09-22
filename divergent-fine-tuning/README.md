# Divergent Fine-Tuning

The article [Active Divergence with Generative Deep Learning - A Survey and Taxonomy](https://arxiv.org/abs/2107.05599) defines these methods in this way:

> Divergent fine-tuning methods take pre-trained models that
generate an approximate distribution P
and fine-tune the
model away from the original training data.

In other words, we can modify the pre-trained model by retraining it with other datasets, for example, or using other models and loss functions to make the new generated set U get further and further away from the original training set.