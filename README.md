# PySlowFast

PySlowFast is an open source video understanding codebase from FAIR that provides state-of-the-art video classification models, including papers "[SlowFast Networks for Video Recognition](https://arxiv.org/abs/1812.03982)", and "[Non-local Neural Networks](https://arxiv.org/abs/1711.07971)". 

<div align="center">
  <img src="demo/ava_demo.gif" width="600px"/>
</div>

PySlowfast 是一个基于 PyTorch 的代码库，让研究者可以轻而易举地复现从基础至前沿的视频识别 (Video Classification) 和行为检测 (Action Detection) 算法。不但如此，PySlowFast 代码库同时开源了大量预训练模型 (pretrain models)，让研究者省去了反复训练模型的烦恼，可以直接使用 FAIR 预训练的前沿 (cutting edge performance) 模型。

PySlowFast 既提供视频理解基线（baseline）模型，还提供了当今前沿的视频理解算法复现。其算法不单单囊括视频视频（video classification），同时也包括行为检测（Action Classification）算法。与当今开源社区中各种视频识别库复现出参差不齐的性能相比，使用 PySlowFast 可轻而易举地复现出当今前沿的模型。


## Introduction

The goal of PySlowFast is to provide a high-performance, light-weight pytorch codebase provides state-of-the-art video backbones for video understanding research on different tasks (classification, detection, and etc). It is designed in order to support rapid implementation and evaluation of novel video research ideas. PySlowFast includes implementations of the following backbone network architectures:

- SlowFast 
- SlowOnly
- C2D
- I3D
- Non-local Network

## Updates

PySlowFast is released in conjunction with our [ICCV 2019 Tutorial](https://alexander-kirillov.github.io/tutorials/visual-recognition-iccv19/).

## License

PySlowFast is released under the [Apache 2.0 license](LICENSE). 

## Model Zoo and Baselines

We provide a large set of baseline results and trained models available for download in the PySlowFast [Model Zoo](MODEL_ZOO.md).

## Installation

Please find installation instructions for PyTorch and PySlowFast in [INSTALL.md](INSTALL.md). You may follow the instructions in [DATASET.md](slowfast/datasets/DATASET.md) to prepare the datasets.

## Quick Start

Follow the example in [GETTING_STARTED.md](GETTING_STARTED.md) to start playing video models with PySlowFast.
