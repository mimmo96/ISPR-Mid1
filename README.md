# ISPR-Mid1

#SHORT DESCRIPTION
Select an image from 4 different themes, for these images, extract the SIFT descriptors using the visual feature detector embedded in SIFT to identify the points of interest. Aggregate all the identified descriptors in a dataset and run k-means to partition the descriptors in clusters. Then analyze the obtained clusters by confronting the descriptors assigned to each cluster with the thematic classes of the images from which they were extracted (confusion matrix ). 


## TASK:

All the image processing assignments require to use the following [dataset](http://download.microsoft.com/download/A/1/1/A116CD80-5B79-407E-B5CE-3D5C6ED8B0D5/msrc_objcategimagedatabase_v1.zip):

The dataset includes original images as well as their semantic segmentation in 9 object classes (i.e. the image files whose name ends  in “_GT”, where each pixel has a value which is the identifier of the semantic class associated to it).  Each file has a name starting with a number from 1 to 8, which indicates the thematic subset of the image, followed by the rest of the file name. This tematic subset can be used for instance as a class for the full image in image classification tasks.

Select four thematic subsets of your choice, out of the total 8 available, and collect all the associated images. For these images, extract the SIFT descriptors using the visual feature detector embedded in SIFT to identify the points of interest. Aggregate all the identified descriptors in a dataset and run k-means (or any clustering algorithm of your choice) on such data to partition the descriptors in clusters. Then analyze the obtained clusters by confronting the descriptors assigned to each cluster with the thematic classes of the images from which they were extracted (in other words, compute a confusion matrix between the clusters and the four thematic images). Discuss your findings. Choice of the number of clusters and of the clustering algorithm is on you (and should be discussed in the report).
