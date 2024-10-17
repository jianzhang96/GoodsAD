# GoodsAD
[IEEE RA-L 2024] A Supermarket Goods Dataset for Unsupervised Anomaly Detection and Segmentation.</br>
Paper: [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10387569) or [arXiv 2307.04956](https://arxiv.org/abs/2307.04956v2)

If you find this work is helpful in your research, please cite:
````
@ARTICLE{10387569,
  author={Zhang, Jian and Ding, Runwei and Ban, Miaoju and Dai, Linhui},
  journal={IEEE Robotics and Automation Letters},
  title={PKU-GoodsAD: A Supermarket Goods Dataset for Unsupervised Anomaly Detection and Segmentation},
  year={2024},
  volume={9},
  number={3},
  pages={2008-2015},
  doi={10.1109/LRA.2024.3352358}}
````

The GoodsAD dataset contains 6124 images with 6 categories of common supermarket goods.  Each category contains multiple goods. All images are acquired with 3000 × 3000 high-resolution. The object locations in the images are not aligned. Most objects are in the center of the images and one image only contains a single object. Most anomalies occupy only a small fraction of image pixels. Both image-level and pixel-level annotations are provided.

Each image is named with 6 digits, with the first three digits representing the category of the product and the last three representing the serial number. The dataset format is same as [MVTec AD](https://openaccess.thecvf.com/content_CVPR_2019/html/Bergmann_MVTec_AD_--_A_Comprehensive_Real-World_Dataset_for_Unsupervised_Anomaly_CVPR_2019_paper.html). Our dataset can be similarly loaded with the python code that loads MVTec AD, such as [mvtec.py](https://github.com/DonaldRR/SimpleNet/blob/main/datasets/mvtec.py) and [dataset.py](https://github.com/hq-deng/RD4AD/blob/main/dataset.py).

The dataset is created by Jian Zhang, Miaoju Ban (Open Lab on Human Robot Interaction, Peking University).

The figure shows the normal and anomalous images of six categories, and the table shows the details of the dataset.
![overview](./dataset.jpg)

|  Category   | Train (good) | Test (good) | Test (defective) | Sum |Anomaly type| Goods types |
|  ----  | ----  | ----  | ----  | ----  | ----  |----  |
| drink_bottle  | 733 | 356 | 425 | 1514 | 3|97|
| drink_can  | 234 | 147 | 147 | 528 | 3|59|
| food_bottle | 1014|243|361|1618|3|60|
|food_box|432|146|251|829|3|57|
|food_package|540|253|230|1023|2|95|
|cigarette_box|183|183|246|612|1|116|
|Sum|3136|1328|1660|6124|-|484|

## Download
The dataset are available at [OneDrive](https://mailhfuteducn-my.sharepoint.com/:f:/g/personal/2015216892_mail_hfut_edu_cn/Eu1ap3oe4OJCmQSpr8ouc4UBFbCT6SQt3d_yCz3R0CgLfQ?e=3svFSB) and [Baidu Disk](https://pan.baidu.com/s/1TJ-0NDUJPWFl8IN8K-p2mw?pwd=go8y).
<!-- 提取码：go8y -->

|Category|Size (GB)|Link1|Link2|
|  ----  | ----  |----  |----  |
|drink_bottle|2.9|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:u:/g/personal/2015216892_mail_hfut_edu_cn/EeoscD4PU4VAoaiTeeGyrgEBRXoibgXiRHACWdRily-i-w?e=YENamB)|[Baidu Disk](https://pan.baidu.com/s/1mnL14Sd5jTWVH7ueA-zStg?pwd=d6mr)|
|drink_can|1.1|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:u:/g/personal/2015216892_mail_hfut_edu_cn/Efs7rgdmVWJKu_eW2RxgswIBr15PdwwoDPnftnLbbjAyAw?e=iMR6Q6)|[Baidu Disk](https://pan.baidu.com/s/1XOsr5Fs0bQ0Ak4_Rhs_aaA?pwd=kg2z)|
|food_bottle|3.0|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:u:/g/personal/2015216892_mail_hfut_edu_cn/ESib3l3xt4NLqEjVq76MykUBqgLsLbeDnSeCMb8YAOKbzg?e=fQDecg)|[Baidu Disk](https://pan.baidu.com/s/1SPuPz6ukOZcIfWIBMg9YhA?pwd=6qrb)|
|food_box|1.7|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:u:/g/personal/2015216892_mail_hfut_edu_cn/EbZlumiFMxZGi2cjIrE-IGYBxiRFEjEBNNZCCI6frPEQVg?e=rMDeRj)|[Baidu Disk](https://pan.baidu.com/s/1zLTB9jIx-UxgDOqFOezS_Q?pwd=m6y8)|
|food_package|2.2|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:u:/g/personal/2015216892_mail_hfut_edu_cn/ETInGCW7EOBKoFmh31-Y8PkB17MKP_iaVOhGLRuWyU1EQA?e=vQMcW4)|[Baidu Disk](https://pan.baidu.com/s/183pAoz7pTPwWkv4jE0aPuw?pwd=j9nc)|
|cigarette_box|1.4|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:u:/g/personal/2015216892_mail_hfut_edu_cn/EU2Lgyz64k1En435HtDAtVMB1GlzidKCUA_tFLUIr5Wq-g?e=ZxabJ7)|[Baidu Disk](https://pan.baidu.com/s/177e2KPZrU5Z1C2rbei0rTg?pwd=nj7a)|

## Pretrained Models
 We also conduct a thorough evaluation of current state-of-the-art unsupervised anomaly detection methods such as PatchCore and SimpleNet on the GoodsAD dataset. The pretained models are available at:
<!-- 提取码：a11j -->
|Link1|Link2|
|  ----  | ----  |
|[OneDrive](https://mailhfuteducn-my.sharepoint.com/:f:/g/personal/2015216892_mail_hfut_edu_cn/EoITUN0LyvFMpEYG2dteBPEB6OX7PH0FPn0Ar2kSlg-QaA?e=HRyXlb)|[Baidu Disk](https://pan.baidu.com/s/1z-IU2DbEHVa9jTEquNuXtw?pwd=a11j)|
