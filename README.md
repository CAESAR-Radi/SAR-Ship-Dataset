# SAR-Ship-Dataset
This dataset labeled by SAR experts was created using 102 Chinese Gaofen-3 images and 108 Sentinel-1 images. It consists of 43,819 ship chips of 256 pixels in both range and azimuth. These ships mainly have distinct scales and backgrounds. It can be used to develop object detectors for multi-scale and small object detection. The details of this dataset is referred to "Wang, Yuanyuan, Chao Wang, Hong Zhang, Yingbo Dong, and Sisi Wei. 2019. "A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds."  Remote Sensing 11 (7). doi: 10.3390/rs11070765." 

It will be released in May.

If you feel this dataset is useful, please cite as the following format.

@Article{rs11070765,
AUTHOR = {Wang, Yuanyuan and Wang, Chao and Zhang, Hong and Dong, Yingbo and Wei, Sisi},
TITLE = {A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds},
JOURNAL = {Remote Sensing},
VOLUME = {11},
YEAR = {2019},
NUMBER = {7},
ARTICLE-NUMBER = {765},
URL = {http://www.mdpi.com/2072-4292/11/7/765},
ISSN = {2072-4292},
ABSTRACT = {With the launch of space-borne satellites, more synthetic aperture radar (SAR) images are available than ever before, thus making dynamic ship monitoring possible. Object detectors in deep learning achieve top performance, benefitting from a free public dataset. Unfortunately, due to the lack of a large volume of labeled datasets, object detectors for SAR ship detection have developed slowly. To boost the development of object detectors in SAR images, a SAR dataset is constructed. This dataset labeled by SAR experts was created using 102 Chinese Gaofen-3 images and 108 Sentinel-1 images. It consists of 43,819 ship chips of 256 pixels in both range and azimuth. These ships mainly have distinct scales and backgrounds. Moreover, modified state-of-the-art object detectors from natural images are trained and can be used as baselines. Experimental results reveal that object detectors achieve higher mean average precision (mAP) on the test dataset and have high generalization performance on new SAR imagery without land-ocean segmentation, demonstrating the benefits of the dataset we constructed.},
DOI = {10.3390/rs11070765}
}
