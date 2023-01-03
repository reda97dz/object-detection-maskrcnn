# Mask-RCNN Object Detection

The project involved training a Mask R-CNN model on a custom dataset of 98 images of Christmas trees. The dataset was split into 78 images for training and 20 images for validation. The images were annotated using VGG Image Annotator.

Due to limited computational resources, the training was performed on Kaggle. However, there were issues with compatibility between the Mask R-CNN code and the version of TensorFlow installed on Kaggle - TensorFlow 2, which the original implementation of Mask R-CNN does not support. To solve this, a modified version of Mask R-CNN (found here: https://github.com/akTwelve/Mask_RCNN) that is compatible with TensorFlow 2 was used. I introduced a slight change to the code to disable multiprocessing that caused issues with training on Kaggle.

## Data and notebook

The notebook and dataset are available on kaggle by following this link: https://www.kaggle.com/code/redaa97/xmas-detection

## Results

Detection results are available in folder splash results
