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

## Running EnzRetro
