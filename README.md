This is update for our SAR-Ship-Dataset! We correct some errors such as bounding box errors and repeat clips. 

Now, the format of label files is ".txt" of which each line represents a ship. Each line of label files consists of five numbers: 

Category of the ship, normalized column value of the ship center in the chip, normalized row value of the ship center, normalized ship width and normalized ship length.

We label all the ships as one category at current stage.

You can also find an old version of our dataset in this site.

Besides, our dataset is so large that you cannot download it direcly, we start LFS service for it and you need to install lfs for your computer and download the dataset 

by command like "git lfs clone https://github.com/CAESAR-Radi/SAR-Ship-Dataset.git". Maybe sometimes, bandwidth of our lfs runs out in current month and you can't download it, 

then it will reset in next month.

This dataset labeled by SAR experts was created using 102 Chinese Gaofen-3 images and 108 Sentinel-1 images. It consists of 39,729 ship chips(remove some repeat clips) of 256 pixels in both range and azimuth. These ships mainly have distinct scales and backgrounds. It can be used to develop object detectors for multi-scale and small object detection. The details of this dataset is referred to "Wang, Yuanyuan, Chao Wang, Hong Zhang, Yingbo Dong, and Sisi Wei. 2019. "A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds." Remote Sensing 11 (7). doi: 10.3390/rs11070765."

Currently, we have released all the dataset for ship detection using SAR images, which has 39,729 ship chips.

If you feel this dataset is useful, please cite as the following format.

@Article{rs11070765, AUTHOR = {Wang, Yuanyuan and Wang, Chao and Zhang, Hong and Dong, Yingbo and Wei, Sisi},

TITLE = {A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds},

JOURNAL = {Remote Sensing},

VOLUME = {11},

YEAR = {2019},

NUMBER = {7},

ARTICLE-NUMBER = {765},

URL = {http://www.mdpi.com/2072-4292/11/7/765},

ISSN = {2072-4292},

DOI = {10.3390/rs11070765}

}

Besides, we own many thanks to China Center for Resources Satellite Data and Application and Copernicus Open Access Hub for providing Gaofen-3 images and Sentinel-1 images, respectively.

This research was funded by the National Natural Science Foundation of China under Grant 41331176 and National Key Research and Development Program of China (2016YFB0501501).
