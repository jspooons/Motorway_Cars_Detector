# Motorway_Cars_Detector

Closely follows the tutorial found here on [Transfer Learning Faster R-CNN](https://medium.com/@natsunoyuki/teaching-a-model-to-become-an-expert-at-locating-cats-and-dogs-in-images-716cdbc8d48f)

Instead of using the cats and dogs dataset, used in the article above, this repo uses the [Traffic Vehicles Object Detection](https://www.kaggle.com/datasets/hasibullahaman/objectdetectiondatasetcar/code) dataset.

The notebook trains a model to detect vehicles on a motorway from a variety of images. Some of the images are taken at night time with lots of cars, some in the day with less cars, which also are closer to the camera. 

The current notebook only finetunes the pre-trained model on the new dataset for 1 epoch and lready produces the following result:

![image](https://github.com/jspooons/Motorway_Cars_Detector/assets/25199093/dd0b8b90-3c28-4309-81d1-d66d15600a98)
