Image segmentation is the process of partitioning an image into multiple segments.It helps to find different groups in an image such that pixels in the same cluster/segment
share certain characteristics. Image segmentation has wide range of applications like segmenting Satellite imagery, Medical Imaging images etc. 

In this project, we use K means clustering to perform segmentation of grey scale and color images.

Run command:

python kmeans_cluster.py -i image -k 3 -m grey
python kmeans_cluster.py -i image -k 2 -m rgb 

User needs to specify the path of image, number of clusters we want the image to be classified into and whether image is grey scale or rgb image. Output images are saved
into /output folder.  

