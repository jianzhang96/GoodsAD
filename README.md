# GoodsAD
A Supermarket Goods Dataset for Unsupervised Anomaly Detection and Segmentation.</br>
Paper: [arXiv 2307.04956](https://arxiv.org/abs/2307.04956)

The GoodsAD dataset contains 6124 images with 6 categories of common supermarket goods.  Each category contains multiple goods. All images are acquired with 3000 × 3000 high-resolution. The object locations in the images are not aligned. Most objects are in the center of the images and one image only contains a single object. Most anomalies occupy only a small fraction of image pixels. Both image-level and pixel-level annotations are provided.

Each image is named with 6 digits, with the first three digits representing the category of the product and the last three representing the serial number. The dataset format is same as MVTec AD.

The dataset is created by Jian Zhang, Miaoju Ban (Open Lab on Human Robot Interaction, Peking University).

The figure shows the normal and anomalous images of six categories, and the table shows the details of the dataset.
![overview](./dataset.jpg)

|  Category   | Train (good) | Test (good) | Test (defective) | Sum | Goods types |
|  ----  | ----  | ----  | ----  | ----  | ----  |
| drink_bottle  | 733 | 356 | 425 | 1514 | 97|
| drink_can  | 234 | 147 | 147 | 528 | 59|
| food_bottle | 1014|243|361|1618|60|
|food_box|432|146|251|829|57|
|food_package|540|253|230|1023|95|
|cigarette_box|183|183|246|612|116|
|Sum|3136|1328|1660|6124|484|

## Download
The dataset are available at [Baidu Disk](https://pan.baidu.com/s/1TJ-0NDUJPWFl8IN8K-p2mw?pwd=go8y).
<!-- 提取码：go8y -->

|Category|Size (GB)|
|  ----  | ----  |
|[drink_bottle](https://pan.baidu.com/s/1mnL14Sd5jTWVH7ueA-zStg?pwd=d6mr)|2.93|
|[drink_can](https://pan.baidu.com/s/1XOsr5Fs0bQ0Ak4_Rhs_aaA?pwd=kg2z)|1.12|
|[food_bottle](https://pan.baidu.com/s/1SPuPz6ukOZcIfWIBMg9YhA?pwd=6qrb)|3.03|
|[food_box](https://pan.baidu.com/s/1zLTB9jIx-UxgDOqFOezS_Q?pwd=m6y8)|1.67|
|[food_package](https://pan.baidu.com/s/183pAoz7pTPwWkv4jE0aPuw?pwd=j9nc)|2.19|
|[cigarette_box](https://pan.baidu.com/s/177e2KPZrU5Z1C2rbei0rTg?pwd=nj7a)|1.45|

 we also conduct a thorough evaluation of current state-of-the-art unsupervised anomaly detection methods on the GoodsAD dataset. The pretained models are available at [Baidu Disk](https://pan.baidu.com/s/1z-IU2DbEHVa9jTEquNuXtw?pwd=a11j).
<!-- 提取码：a11j -->
