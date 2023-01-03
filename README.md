# Mask-RCNN Object Detection

The project involved training a Mask R-CNN model on a custom dataset of 98 images of Christmas trees. The dataset was split into 78 images for training and 20 images for validation. The images were annotated using VGG Image Annotator.

Due to limited computational resources, the training was performed on Kaggle. However, there were issues with compatibility between the Mask R-CNN code and the version of TensorFlow installed on Kaggle - TensorFlow 2, which the original implementation of Mask R-CNN does not support. To solve this, a modified version of Mask R-CNN ([found here](https://github.com/akTwelve/Mask_RCNN)) that is compatible with TensorFlow 2 was used. I introduced a slight change to the code to disable multiprocessing that caused issues with training on Kaggle.

## Data and notebook

The notebook and dataset are available on kaggle by following [this link](https://www.kaggle.com/code/redaa97/xmas-detection)

The dataset can also be downloaded from [this link](https://github.com/reda97dz/object-detection-maskrcnn/releases/download/0.1/xmas_trees_dataset.zip)

## Results

Detection results are available in folder splash results

## Trained model

Trained model can be downloaded from the logs folder in the kaggle notebook or by clicking [this link](https://www.kaggleusercontent.com/kf/115331467/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..RH47yfqTK0D8uuuggrbVow.nb5TkrIxetl-Sh8L5gELXSCu-9DNr5m2yyUWskklyB-h8_0NVofx7Yrm_-oVMf8UXP4ay-9hVnISFqu2rLguw42ev25dw8M7g6AtABLY8WvD12MJHQsTTh3MIec1ZwAi4FKJdxXP_00a-Nuj2Q_WtfCZvhONQ8NSr-T_5PoJfjjGIu6Ir05AnAttlk94saKZUSFIXhwuM3HxRvv_ckCTB-uMlGm2vtIxeneJkkHPB1UhCg6lbJzKbf6R6hvSupDLCtmEIljVh-j-_1LtOwrHc6zXCTi9FjNvBDWlP07jHLjXPfr0p3iXxAwCgcN2_tdfEl5bfG6qbWPYh_a4IivTliPYBAC8aKE5TSYjCP3Hyy-mWNF7VXZk4PQLDaOKKBmta-ovjTjROTIDKSU4fNsPJO66XpHu2zC_IZK7te5du4BvyyX00NZ3V9GMO4splQ0gZ37EpbL46Ip5-L9ur9BXWtGwtOCCvCUFY9DgCBbAN4SMx4OqieQleOXQjENr7y-aE4NrgfDXyOqaYWO-jsuT1N2vwwrK3TH_QD_OmziDc86v3QD5UzcSVK_l6YzPJ_iXRvKbUoXOwequj3TwDj8WsDVWY8NJA0WIYbA0_xbpKZxn7RFpO9AsX1ZRQaMcVTAYPivthPefjk_HTXBcdn30ug.2hXCwwGE1AQZBQYUpkY7nQ/logs/balloon20230102T1247/mask_rcnn_balloon_0005.h5)
