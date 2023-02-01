# GAN

> [Paper_Review](https://inhopp.github.io/paper/Paper15/)

| Epoch 0 | Epoch 50 | Epoch 100 | Epoch 150 | Epoch 200 |
|:-:|:-:|:-:|:-:|:-:|
| ![data0](https://user-images.githubusercontent.com/96368476/215316520-03512d96-1d3b-4eae-b16a-30c7e042c5fc.png) | ![data49](https://user-images.githubusercontent.com/96368476/215966207-8d1bda32-d668-4327-a32a-21bcf931acba.png) | ![data99](https://user-images.githubusercontent.com/96368476/215966213-d543afff-1544-4abb-838a-23e8b4e3abda.png) | ![data149](https://user-images.githubusercontent.com/96368476/215966218-64d2aa57-8c2d-4c37-84e0-15447f89fe64.png) | ![data199](https://user-images.githubusercontent.com/96368476/215966222-1c40f762-9e3e-49a6-b7a8-0e0a30e1fda6.png) |


## Repository Directory 

``` python 
├── DCGAN
     ├── datasets
     │     └── mnist
     ├── data.py
     ├── option.py
     ├── model.py
     ├── train.py
     └── README.md
```

- `data.py` : data load (download mnist)
- `data/dataset.py` : data preprocess & get item
- `model.py` : Define block and construct Model
- `option.py` : Environment setting

<br>


## Tutoral

### Clone repo and install depenency

``` python
# Clone this repo and install dependency
git clone https://github.com/inhopp/DCGAN.git
```

<br>


### train
``` python
python3 train.py
    --device {}(default: cpu) \
    --input_size{}(default: 28) \
    --lr {}(default: 0.0002) \
    --n_epoch {}(default: 200) \
    --num_workers {}(default: 4) \
    --batch_size {}(default: 64) \
```


<br>


#### Main Reference
https://github.com/eriklindernoren/PyTorch-GAN