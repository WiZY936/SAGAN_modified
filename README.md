# SAGAN_modified

## Dataset
CelebA 
```bash
https://drive.google.com/drive/folders/0B7EVK8r0v71pWEZsZE9oNnFzTm8?resourcekey=0-5BR16BdXnb8hVj6CNHKzLg
```

## Usage

Train a model with a target attribute

```bash
python train.py --experiment-name celeba_128_eyeglasses --target-attr Eyeglasses --gpu
```

Generate images from trained models

```bash
python generate.py --experiment-name celeba_128_eyeglasses --gpu
```
