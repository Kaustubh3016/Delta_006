# Image Deraining using ResNet

This project removes rain streaks from images using a ResNet-based deep learning model.

## Dataset

This project uses the **Rain100H** dataset.

Download it from:
https://www.kaggle.com/datasets/nguynhoitrung/rain100h

After downloading, extract the dataset and place it in the project directory as shown below:

```
DeLTA_006/
│── clear_img_from_rainy_img_ResNet.ipynb
│── resnet_derain_rain100h.pth
└── Rain100H/
    ├── train/
    └── test/
```

## Installation

```bash
pip install torch torchvision matplotlib pillow opencv-python
```

## Run

Open the notebook:

```
clear_img_from_rainy_img_ResNet.ipynb
```

and execute all cells.

## Project Structure

```
DeLTA_006/
│── clear_img_from_rainy_img_ResNet.ipynb
│── resnet_derain_rain100h.pth
└── Rain100H/
    ├── train/
    └── test/
```
