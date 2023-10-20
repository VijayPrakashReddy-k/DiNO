# DiNO

self-**Di**stillation with **NO** labels

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![PyTorch 2.0](https://img.shields.io/badge/torch-v2.0-brightgreen)](https://pytorch.org/docs/stable/index.html)
[![PyTorch-Lightning](https://img.shields.io/badge/pytorch_lightning-v2.0.6-orange)](https://lightning.ai/docs/pytorch/latest/)
[![Torchvision 0.15](https://img.shields.io/badge/torchvision-v0.15-green)](https://pytorch.org/vision/stable/index.html)
[![Transformers](https://img.shields.io/badge/Transformers-v4.34.0-lightgreen)](https://huggingface.co/docs/transformers/index)
[![Albumentations](https://img.shields.io/badge/Albumentations-v1.3.1-yellow)](https://albumentations.ai/docs/)

**contents:**

- [self-Distillation with NO labels](./README.md/#DINO)

- [DiNO Architecture](./README.md/#dino-architecture)
  
- [Core Concepts](./README.md/#TERMS)
- [Assignment](./README.md/#Assignment)
- [DEMO](./README.md/#demo)

<h1 align = 'center', id = "DINO"> Self-Distillation with No Labels (DINO) </h1>

[DINO (Distillation with No Labels)](./CONCEPTS.md/#DINO) is a method applied to the [Vision Transformer (ViT)](./CONCEPTS.md/#VIT) using a [self-supervised learning](./CONCEPTS.md/#SSL) approach. This technique reveals that the self-supervised features from ViT inherently possess information pertinent to the [semantic segmentation](./CONCEPTS.md/#seg) of images. Moreover, these extracted features serve as highly effective [k-NN classifiers](./CONCEPTS.md/#KNN).

