# EfficientTTS
## Unofficial Pytorch implementation of "EfficientTTS: An Efficient and High-Quality Text-to-Speech Architecture"([ArXiv](https://arxiv.org/abs/2012.03500)).

## Current status
- [x] Implementation of EFTS-CNN + HifiGAN ([Generated-samples](https://github.com/liusongxiang/efficient_tts/tree/main/egs/lj/current-gen-waves-130000steps))

## Setup with virtualenv

```
$ cd tools
$ make
# If you want to use distributed training, please run following
# command to install apex.
$ make apex
```

Note: If you want to specify Python version, CUDA version or PyTorch version, please run for example:

```
$ make PYTHON=3.7 CUDA_VERSION=10.1 PYTORCH_VERSION=1.6
```

## Training
Please go to egs/lj folder, and see run.sh for example use.

## Acknowledgement
The code framework is from https://github.com/kan-bayashi/ParallelWaveGAN


