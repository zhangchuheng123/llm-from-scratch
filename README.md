# llm-from-scratch

## Setup Environment

```bash
git clone git@github.com:zhangchuheng123/llm-from-scratch.git
curl -O https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh
bash Anaconda3-2024.06-1-Linux-x86_64.sh
conda create -n llm python=3.10
conda activate llm
conda install pytorch torchvision torchaudio cpuonly -c pytorch
conda install matplotlib pandas
pip install tiktoken tqdm tensorflow
```

## Setup Environment with conda installed

```bash
conda create -n llm python=3.10
conda activate llm
conda install pytorch torchvision torchaudio cpuonly -c pytorch
conda install matplotlib pandas
pip install tiktoken tqdm tensorflow
```

## Setup Environment without conda

```bash
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pytorch matplotlib pandas tiktoken tqdm tensorflow
```

## Pre-training 

```bash
python pretrain.py
```

## Fine-tuning 

```bash
python finetune.py
```

## Disclaimer

The code is adopted from the original code repo https://github.com/rasbt/LLMs-from-scratch of the book "Build a Large Language Model (From Scratch)".

This directory follows the Apache 2.0 lisence according to the license of the original repo.
