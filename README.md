# UBC-dataset
Urban Building Classification dataset

## Update!
We have finished our work on UBCv2! Please go to the UBCv2 branch for more details.
- 
## Introduction
We present a dataset for building detection and classification from very high-resolution satellite imagery with the focus on object-level interpretation of individual buildings.
It is meant to provide not only a flexible test platform for object detection algorithms but also a solid basis for the comparison of city morphologies and the investigation of urban planning.

The details of this dataset can be seen in paper 'Urban Building Classification (UBC) – A Dataset for Individual Building Detection and Classification from Satellite Imagery' (Link will be added after the publication).

Here is an example of the annotation.

<img src="./example.png" width="350" height="350" />

Input image (a), building footprints (b, green polygons), roof types (c) and functions (d, coarse classes)

## Download
Currently, we only provide the standard [COCO](https://cocodataset.org/#home) instance segmentation format.

Annotations of roof coarse, roof fine and use coarse are build. 

The train and valitation set of this dataset can be downloaded from:

BaiduNetdisk: [https://pan.baidu.com/s/1M6yYD1lvbqsVpn5MHGa2tg?pwd=7hbm](https://pan.baidu.com/s/1M6yYD1lvbqsVpn5MHGa2tg?pwd=7hbm) password: 7hbm

Google Grive: [https://drive.google.com/file/d/1XnKFKqjoa95PLXFw01HcXx4Az49Qw37i/view?usp=sharing](https://drive.google.com/file/d/1XnKFKqjoa95PLXFw01HcXx4Az49Qw37i/view?usp=sharing)
## References
If you use our dataset, please cite our CVPR EarthVision 2022 paper:
```
@INPROCEEDINGS{9857458,
  author={Huang, Xingliang and Ren, Libo and Liu, Chenglong and Wang, Yixuan and Yu, Hongfeng and Schmitt, Michael and Hänsch, Ronny and Sun, Xian and Huang, Hai and Mayer, Helmut},
  booktitle={2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)}, 
  title={Urban Building Classification (UBC) – A Dataset for Individual Building Detection and Classification from Satellite Imagery}, 
  year={2022},
  volume={},
  number={},
  pages={1412-1420},
  doi={10.1109/CVPRW56347.2022.00147}}
```
