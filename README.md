# Neural-style-transfer-pytorch
Neural Style Transfer implementation using PyTorch
# Neural Style Transfer using PyTorch

## Overview
This project implements Neural Style Transfer (NST) using PyTorch. It combines the content of one image with the artistic style of another image.

## Features
- Pretrained VGG-based encoder
- Content and style image datasets
- PyTorch model implementation
- Configurable training parameters
- Training progress and loss monitoring

## Technologies
- Python
- PyTorch
- Torchvision
- Pillow
- tqdm

## Project Structure
```text
NST_Code/
├── content_data/
├── style_data/
├── utils/
│   ├── models.py
│   └── utils.py
├── train.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation
Create and activate a virtual environment, then install dependencies:

```bash
python -m venv venv
```

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Pretrained Weights
Download or obtain the compatible pretrained VGG weights required by the model. Place them in the configured location before training. Do not commit large weights unless permitted and appropriate.

## Training
Run:

```bash
python train.py --experiment experiment2
```

## Status
This project is a learning implementation of Neural Style Transfer. Check the code and configuration for the current training features and supported options.
