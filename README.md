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
