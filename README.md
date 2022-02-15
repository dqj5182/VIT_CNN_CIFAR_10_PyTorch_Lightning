# SNU_CV_VIT_CIFAR

Folder Structure
```bash
.
├── model
│   ├── HCGNet
│   ├── densenet
│   ├── dla
│   ├── dpn
│   ├── efficientnet
│   ├── efficientnetV2
│   ├── mobilenetV3
│   ├── resnet
│   ├── resnext
│   ├── vgg
│   └── vit
├── notebooks
│   └── Pretrained ResNet (VIT Week).ipynb
├── utils
│   ├── autoaugment.py
│   ├── dataaug.py
│   └── utils.py
├── weights
├── main.py
└── setup.sh           
```

Train the model with CIFAR-10 dataset:
```
python main.py --dataset c10 --label-smoothing --autoaugment --model-name [name of the model]
```

</br>

## Pretrained Models
Epoch: 200 (CNN based), Epoch: 350 (VIT)
Model | Pretrained (.pth) | Notebook | Paper | Accuracy
--- | --- | --- | --- | ---
Vision Transformer | [Google Drive](https://drive.google.com/file/d/14E9-efY8Z8qvg8QoyEl0m20FMGRt2g8P/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/1faGg8XctN22cFthUa_8MdhsqgDrPh7xZ?usp=sharing) | [Arxiv](https://arxiv.org/pdf/2010.11929.pdf) | 89.72%
ResNet-50 | [Google Drive](https://drive.google.com/file/d/1FNsXhHEpEKiZQFgk8vBppmGIABEYXb88/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/1NSBEJSnQ4wgt6_bvPPKlbyxASZcZgfH6?usp=sharing) | [Arxiv](https://arxiv.org/pdf/1512.03385.pdf) | 95.36%
ResNeXT | [Google Drive](https://drive.google.com/file/d/1LBn_AVSaQv1O0LaGN8JUWwwyFQ5_mIwl/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/1yTg8EmAi2yVpKBthnh-S47sG6dPEoQxD?usp=sharing) | [Arxiv](https://arxiv.org/pdf/1611.05431.pdf) | 94.91%
HCGNet | [Google Drive](https://drive.google.com/file/d/1jNDtVZTB9DAWB9ZzaVUbF-sE2-LsMq1O/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/10Ey9Dc2Va3b2O-L15a27AqOXj7cYtMtm?usp=sharing) | [Arxiv](https://arxiv.org/pdf/1908.09699.pdf) | 94.76%
DenseNet | [Google Drive](https://drive.google.com/file/d/1NVe2wwJLxL1XH1tbenrVU7iV5Tx3DuyL/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/197uig6UEecpbLIswSKps4Fu4oaRN1yuS?usp=sharing) | [Arxiv](https://arxiv.org/pdf/1608.06993.pdf) | 94.59%
VGG-19 | [Google Drive](https://drive.google.com/file/d/1kNcRFOpmotVaKER9ThTpYIdWQg_p8_Ab/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/1bxbpmPQsnb1DzwQGz1m9QTacUDwBkGh7?usp=sharing) | [Arxiv](https://arxiv.org/pdf/1409.1556.pdf) | 94.37%
VGG-11 | [Google Drive](https://drive.google.com/file/d/1h4C4WQHqVhGOHKyCkk41unA_A9Ao4R3h/view?usp=sharing) | [Google Colab](https://colab.research.google.com/drive/1DOPFU3J6_mxVDCvJLH9lBL1rbH84LGrD?usp=sharing) | [Arxiv](https://arxiv.org/pdf/1409.1556.pdf) | 92.72%

</br>


## Reference
https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html</br>
https://github.com/lukemelas/EfficientNet-PyTorch</br>
https://github.com/facebookresearch/LaMCTS</br>
https://github.com/kekmodel/MPL-pytorch</br>
https://github.com/MadryLab/cifar10_challenge</br>
https://github.com/xiaolai-sqlai/mobilenetv3</br>
https://github.com/EN10/CIFAR</br>
https://medium.com/@sergioalves94/deep-learning-in-pytorch-with-cifar-10-dataset-858b504a6b54</br>
