# Object Detection for Sweeping Robots In the Home Scene (ODSR-IHS)：A new benchmak dataset

1. About ODSR-IHS

Object detection plays an important role in computer vision. It has a variety of applications, including security detection, vehicle recognition, and service robots. With the continuous improvement of public databases and the development of deep learning, object detection has witnessed significant breakthroughs. However, the object detection of sweeping robots during operations should consider various factors, including the camera angle, indoor scenery, and identification of object category. To the best of our knowledge, no corresponding database on these conditions has been developed. 

In this study, we propose a large-scale publicly available benchmark dataset called object detection for sweeping robots in home scenes (ODSRIHS). The dataset has 6,000 images and 16,409 instances of 14 object categories.  

2. Collection Method

The data mainly reflect the complex indoor environments, with various target shapes and a considerable proportion of flexible and small targets. In the process of data collection, the following principles are satisfied:  

(1) The ratio of sunny to cloudy weather is not higher than 9:1.
(2) The ratio of day to night is not higher than 4: 1.
(3) The number of indoor scenes is not less than 50.
(4) The acquisition angle is consistent with that of an actual sweeping robot  

These 14-object classes include bed, sofa, cabinet, stool, table, close stool, trashcan, slippers, wire, socks, carpet, book, feces, and curtain.

3. Some  examples and calibration 

The data set is divided into 4 folders, respectively named Annotations, ImageSets, JPEGImages, labels. In the Annotations folder, the xml format tag file corresponding to each picture is saved. The specific information is the file name, image size, object category and bounding box coordinate information of each picture. The JPEGImages folder contains all the picture information, which can be divided into training set, validation set and test set according to specific needs. The visualization of some data sets is shown in the figure.

![image-20210507105136152](C:\Users\lvyon\AppData\Roaming\Typora\typora-user-images\image-20210507105136152.png)

![image-20210507105149514](C:\Users\lvyon\AppData\Roaming\Typora\typora-user-images\image-20210507105149514.png)

4. Learn more

Main paper: (Y. Lv, Y. Fang, W. Chi, G. Chen and L. Sun, "Object Detection for Sweeping Robots in Home Scenes (ODSR-IHS): A Novel Benchmark Dataset," in *IEEE Access*, vol. 9, pp. 17820-17828, 2021, doi: 10.1109/ACCESS.2021.3053546.)

If you use this data set, please cite this paper:

 https://ieeexplore.ieee.org/document/9333554

(1) Explains the dataset and how the data is collected

(2) Use mainstream algorithms based on deep learning to verify the data set

(3) Transplant the trained model to the chip for verification
