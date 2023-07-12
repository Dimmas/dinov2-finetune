# dinov2-finetune
Finetuning DINOv2 (https://github.com/facebookresearch/dinov2) on your customized dataset.

First download dinov2: `git clone https://github.com/Dimmas/dinov2-finetune.git, 
and then run finetuning by 

```python dinov2_finetune.py --arch dinov2_vitb14 --resolution 112 --epochs 10 --data-dir PATH_TO_DATASET```. 

`--arch` can also be `dinov2_vitl14`.
