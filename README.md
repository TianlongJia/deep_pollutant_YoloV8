# Detecting the interaction between microparticles and biomass in biological wastewater treatment process with Deep Learning method

This repository contains the code used for the following publication:
```bash
  To do: XXXXXXXX
```

The aim of this repository is to use the YOLOv8 model to detect the interaction between microparticles and biomass in biological wastewater treatment process.

![summary_figure](figures/Graphical_abstract.jpg)


Acknowledgement:

This repository was inspired by the work of Ultralytics YOLOv8 (https://github.com/ultralytics/ultralytics). 
Learn more about Ultralytics YOLOv8 at [documentation](https://docs.ultralytics.com/).


## Dataset

"XXX" dataset is a new labelled dataset for detecting the interaction between microparticles and biomass in biological wastewater treatment process. This dataset and further details can be found in:

```bash
  To do: XXXXXXXX
```

## Installation:

Requirements:
- Windows 10 or Linux
- Python 3.8.16
- Pytorch 1.13.1

(1) Install Pytorch 1.13.1 (CUDA 11.7) (for Windows 10)

```bash
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia
```

(2) Install other packages

```bash
  pip install -r requirements.txt
```

## Note
This repository only includes the implementation of YOLOv8. The implementation of other six model architectures can be found [here](https://github.com/TianlongJia/deep_pollutant), including  (1) Mask RCNN (ResNet50), (2) Mask RCNN (ResNet101), (3) Cascade Mask RCNN(ResNet50), (4) Cascade Mask RCNN(ResNet101), (5) Yolact (ResNet50), and (6) Yolact (ResNet101). 


## Usage

-  `main_Train_IS.ipynb` is the code for training YOLOv8 model for object detection.
-  `main_Evaluate_IS.ipynb` is the code for (1) evaluating model performances on test sets (e.g., outputing mAP50), and (2) predicting objects in images.

## Citing this dataste or paper

If you find this code and dataset are useful in your research or wish to refer to the paper, please use the following BibTeX entry.

```BibTeX
XXXXX
```

## Authors

- [@Tianlong Jia](https://github.com/TianlongJia)
- [@Jing Yu](https://github.com/yyyuj)


## Contact

➡️ Tianlong Jia ([T.Jia@tudelft.nl](mailto:T.Jia@tudelft.nl))

