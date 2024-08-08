# Brain_Tumor_Net
## 数据集 
### 1、脑瘤检测数据集为：https://www.kaggle.com/datasets/davidbroberts/brain-tumor-object-detection-datasets/data
### 2、脑瘤分类数据集为：https://www.kaggle.com/datasets/fernando2rad/brain-tumor-mri-images-44c/data

## 方法
### 1、yolov10 https://github.com/THU-MIG/yolov10
### 2、convnext等主干 https://github.com/huggingface/pytorch-image-models

## 实验结果
### 1、yolo10和yolo10new分别是基线方法和自己改进的新模块，其各自效果如下：
![GitHub Logo](https://github.com/starsky68/Brain_Tumor_Net/blob/main/BT_det.png)
### 2、convnext等基线对比，带new的为新模块的加入效果，其各自效果如下：
![GitHub Logo](https://github.com/starsky68/Brain_Tumor_Net/blob/main/BT_cls.png)
