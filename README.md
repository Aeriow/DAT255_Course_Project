# DAT255 Course Project

This repository contains the results of the DAT255 course project, about food recognition from images.  
The goal of the project was to detect individual food items in a given image.

# Libraries Used

pycocotools API: For loading parsing and visualizing the COCO annotations.  
opencv: For creating mask files and writing them to disk.  
fastai: For training and fine-tuning the model.

# Dataset Used

The dataset used in this project is from: https://www.aicrowd.com/challenges/food-recognition-benchmark-2022.  
This dataset contains:  
* public\_training\_set\_release\_2.1.tar.gz: This is the Training Set of 54,392 (as RGB images) food images, along with their corresponding 100,256 annotations from 323 food classes in MS-COCO format.

* public\_validation\_set\_2.1.tar.gz: This is the suggested Validation Set of 946 (as RGB images) food images, along with their corresponding 1708 annotations from 323 food classes in MS-COCO format.

* public\_test\_release\_2.1.tar.gz: This is the Public Test Set for Food Recognition Benchmark 2022: Round 1.

# Results

The model doesn't quite work as we would like. It is able to detect where in the image food items are,  
but is not able to give us the specific food items present.
