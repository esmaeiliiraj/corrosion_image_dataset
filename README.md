# Corrosion Segmentation Dataset and Code

This repository contains supporting material for the corrosion segmentation study using a multi-source image dataset and a U-Net-based model with a ResNet50 backbone and CBAM attention modules.

## Dataset

The compiled dataset contains images from three main sources:

- Virginia Tech Corrosion Condition State Semantic Segmentation Dataset: https://data.lib.vt.edu/articles/dataset/Corrosion_Condition_State_Semantic_Segmentation_Dataset/16624663
- Corrosion Image Data Set for Automating Scientific Assessment of Materials Dataset: https://arl.wpi.edu/corrosion_dataset/
- Publicly available Roboflow datasets


## Roboflow sources

The Roboflow image pool was collected from the following publicly available projects:

1. Detection Corrosion Nico  
   https://universe.roboflow.com/tcc-bz0mu/detection-corrosion-nico

2. Dataset Adaptado  
   https://universe.roboflow.com/tcc-bz0mu/dataset-adaptado

3. Data Augmentation  
   https://universe.roboflow.com/tcc-bz0mu/data-augmentation-3afv8

4. Corrosion Detection  
   https://universe.roboflow.com/yolocorrosionrustdetection/corrosion-detection-qbdpa

5. Corrosion Detection  
   https://universe.roboflow.com/annotation-scdwy/corrosion-detection-vwqfx

6. Steel Defect-Seg  
   https://universe.roboflow.com/emergency/steel-defect-seg-gd6ok

7. Detect Corrosion IS  
   https://universe.roboflow.com/computervision-a8zib/detect_corrosion_is

8. Dataset Corrosao
   https://universe.roboflow.com/corrosao/dataset-corrosao-faca2

9. Dataset Corrosao Segmentation Semantic IoU  
   https://universe.roboflow.com/corrosao/dataset-corrosao-segmentation-semantic-iou

10. Dataset Corrosao  
    https://universe.roboflow.com/computervision-a8zib/dataset-corrosao

11. Rust Detection  
    https://universe.roboflow.com/rust-detection/rust-detection-38s6e

12. Rush Corrosion Detection  
    https://universe.roboflow.com/yolocorrosionrustdetection/rush_corrosion_detection

The corresponding Roboflow project information indicates a CC BY 4.0 license.

## Data availability

Third-party images are not redistributed directly in this repository. The original source links are provided above to identify the datasets used in the study.

The repository also provides the dataset split information and the code used for preprocessing, augmentation, model training, and evaluation.
