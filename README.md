# GAFNet: A Global Fourier Self Attention Based Novel Network for multi-modal downstream tasks

In “vision and language” problems, multimodal inputs
are simultaneously processed for combined visual and textual understanding for image-text embedding. In this paper,
we discuss the necessity of considering the difference between the feature space and the distribution when performing multimodal learning. We deal with this problem through
deep learning and a generative model approach. We introduce a novel network, GAFNet (Global Attention Fourier
Net), which learns through large-scale pre-training over
three image-text datasets (COCO, SBU, and CC-3M), for
achieving high performance on downstream vision and language tasks. We propose a GAF (Global Attention Fourier)
module, which integrates multiple modalities into one latent
space. GAF module is independent of the type of modality, and it allows combining shared representations at each
stage. Various ways of thinking about the relationships between different modalities directly affect the model’s design.
In contrast to previous research, our work considers visual
grounding as a pretrainable and transferable quality instead of something that must be trained from scratch. We
show that GAFNet is a versatile network that can be used
for a wide range of downstream tasks. Experimental results demonstrate that our technique achieves state-of-theart performance on multimodal classification on the CrisisMD dataset and image generation on the COCO dataset.
For image-text retrieval, our technique achieves competitive
performance.


- If your using our code please cite our paper

```
@inproceedings {susladkar2023GAFNet,
title            = "GAFNet: A Global Fourier Self Attention Based Novel Network for multi-modal downstream tasks",
year             = "2023",
author           = "Onkar Susladkar and Gayatri Deshmukh and Dhruv Makwana and Sparsh Mittal and R Sai Chandra Teja and Rekha Singhal",
booktitle        = "IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)",
address          = "Hawaii, USA",
}
```
