# Randomly_Wired_NN
Replication project of Exploring Randomly Wired Neural Networks for Image Recognition (FAIR)

> You can see original paper in here
> https://arxiv.org/abs/1904.01569

In this project, we implemented smaller version of randomly wired neural networks. Nowadays, neural architecture search(NAS) studies can efficiently find the optimal neural net structure, but the space of possible wirings is constrained and still needs manual design for some parts. This research introduced randomly wired neural networks based on mathematical random graph. Mathematical random graph has less constraints compare to NAS, so we can attempt more free designs of network.

We used CIFAR-10 dataset instead of ImageNet dataset because of H/W limit.

As a result, we confirmed that the randomly wired neural net model can produce similar or better performance to the existing effective models.
