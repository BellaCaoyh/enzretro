# EnzRetro: Enzymatic Retrosynthetic Planning with Site-specific Reaction Edits based on Sequence Generative Architecture 
![](imgs/overview.png)

## Installation 

```bash
conda create enz python=3.8 -y
conda activate enz
pip install -r requirements.txt
```

### Databases
```bash
bypy downfile dataset.zip ./
unzip dataset.zip
rm dataset.zip
```
### Model parameters
```bash
cd model
bypy downfile ecreact.zip ./
unzip ecreact.zip ./
rm ecreact.zip
cd ..
```

## Files Introduction

config：              包含了XXX_config.json文件的模板

extractor:            包含生化反应模板提取相关代码

data：                用于存放数据

model：               用于存放模型和检查点

tokenizer：           存放常用的tokenizer

trainer:              训练器类、训练器配置类

data.py:              Dataset类

model.py:             模型类、模型层类、模型块类、模型配置类

test.py:              测试案例

train.py:             训练案例

## Running EnzRetro
