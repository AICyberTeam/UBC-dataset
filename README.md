# UBC-dataset
A Fine-grained Urban Building Classification dataset

## Update!
We have finished our work on UBCv2! There are two improvements in the UBCv2 dataset:
- 20 global cities with various layouts and styles.
- RGB and SAR image pairs for multi-modal research.

We have submitted the UBCv2 paper to IEEE Transactions on Geoscience and Remote Sensing. The complete UBCv2 dataset will be available after the publication of paper.
In this paper, we propose a Class-wise Geometrical Transformer (CGT) module to improve the performance of general two-stage instance segmentation models for fine-grained building classification.

## Introduction of UBCv2
UBCv2 consists of VHR optical images of 20 unique cities worldwide, for 17 of them finely aligned pairs of optical and Synthetic Aperture Radar (SAR) images are available. An extensive annotation is performed for about 0.5 million building instances with individual polygons and fine-grained roof type category with 12 classes. The annotation of building functions of two cities in the previous version (UBCv1) is also integrated.

Here is four typical cities in UBCv2.

<img src="./UBCv2_examples.png" width="400" height="600" />

Four selected urban areas with typical architectural characteristics (left) and annotation details in the image tiles (right) in the UBCv2 dataset. Colors indicate various classes of roof types. Buildings in different cities show a large diversity of layout as well as architectural style.

Here is a RGB and SAR image pair example in UBCv2.

<p float="left">
  <img src="./UBCv2_examples.png" width="200" />
  <img src="./UBCv2_examples.png" width="200" /> 
</p>


## Introduction of UBCv1
We present a dataset for building detection and classification from very high-resolution satellite imagery with the focus on object-level interpretation of individual buildings.
It is meant to provide not only a flexible test platform for object detection algorithms but also a solid basis for the comparison of city morphologies and the investigation of urban planning.

The details of this dataset can be seen in paper [Urban Building Classification (UBC) – A Dataset for Individual Building Detection and Classification from Satellite Imagery](https://ieeexplore.ieee.org/document/9857458/).

Here is an example of the annotation.

<img src="./example.png" width="350" height="350" />

Input image (a), building footprints (b, green polygons), roof types (c) and functions (d, coarse classes)

## Download
Currently, we only provide the standard [COCO](https://cocodataset.org/#home) instance segmentation format.

# UBCv1
Annotations of roof coarse, roof fine and use coarse are build. 

The train and valitation set of this dataset can be downloaded from:

BaiduNetdisk: [https://pan.baidu.com/s/1M6yYD1lvbqsVpn5MHGa2tg?pwd=7hbm](https://pan.baidu.com/s/1M6yYD1lvbqsVpn5MHGa2tg?pwd=7hbm) password: 7hbm

Google Grive: [https://drive.google.com/file/d/1XnKFKqjoa95PLXFw01HcXx4Az49Qw37i/view?usp=sharing](https://drive.google.com/file/d/1XnKFKqjoa95PLXFw01HcXx4Az49Qw37i/view?usp=sharing)

# UBCv2
Fine-grained building roof instance segmentation. 

The train and valitation set of this dataset can be downloaded from:

BaiduNetdisk: link will be added after the publication.

Google Grive: link will be added after the publication.

Multi-modal fine-grained building roof instance segmentation (RGB + SAR). 

The train and valitation set of this dataset can be downloaded from:

BaiduNetdisk: link will be added after the publication.

Google Grive: link will be added after the publication.

## References
If you use the UBCv1 dataset, please cite our paper on CVPR workshops, 2022:
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
The citation of UBCv2 link will be added after the publication.
