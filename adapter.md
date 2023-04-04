# Adapter
## Parameter-Efficient Transfer Learning for NLP [[PDF]](https://arxiv.org/pdf/1902.00751.pdf) [[code]](https://github.com/google-research/adapter-bert)
- Motivation: fine-tuning is parameter inefficient: an entire new model is required for every task.
- As an alternative, we
propose transfer with adapter modules. Adapter
modules yield a **compact and extensible** model;
they **add only a few trainable parameters per task**( **Compact** models are those
that solve many tasks using a small number of additional
parameters per task. **Extensible** models can be trained in-
crementally to solve new tasks, without forgetting previous
ones. ),
and new tasks can be added without revisiting
previous ones. The parameters of the original
network remain fixed, yielding a **high degree of
parameter sharing**. 
***
![architecture](https://github.com/rockypoo123/papers/blob/main/imgs/adapter.jpg 'architecture of adapter')
