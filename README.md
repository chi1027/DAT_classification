# Vision Transformer with Deformable Attention

Fork from https://github.com/LeapLabTHU/DAT

## Implementation Environment:

Google Colaboratory

## Additional Dependencies in Colab:
- timm 
- einops
- yacs

## Usage of Evaluation:
```
bash evaluate.sh <gpu_nums> <path-to-config> <path-to-pretrained-weights> <path-to-imagenet>
```
or just run `implementation.ipynb` on colab (remember to change the file path)

- imagenet version: ILSVRC 2012
- imagenet structure:
```
imagenet
├── train
│   ├── class folder
│   │    ├── picture
│   │    ├── ...
│   ├── class folder
│   │    ├── picture
│   │    ├── ...
│   └── ...
└── val                   
    ├── class folder
    │    ├── picture
    │    ├── ...
    ├── class folder
    │    ├── picture
    │    ├── ...
    └── ...            
```

