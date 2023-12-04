# Motorway_Cars_Detector

Closely follows the tutorial found here on [Transfer Learning Faster R-CNN](https://medium.com/@natsunoyuki/teaching-a-model-to-become-an-expert-at-locating-cats-and-dogs-in-images-716cdbc8d48f)

Instead of using the cats and dogs dataset, used in the article above, this repo uses the [Traffic Vehicles Object Detection](https://www.kaggle.com/datasets/hasibullahaman/objectdetectiondatasetcar/code) dataset.

The notebook trains a model to detect vehicles on a motorway from a variety of images. Some of the images are taken at night time with lots of cars, some in the day with less cars, which also are closer to the camera. The current code is setup to run through it quickly, so the resulting model is not very good. However, it is clear that for clear images taken in the day time, with vehicles closer to the cameras, the model is able to predict positons of vehicles (albeit with low confidence scores, but again training the model with more epochs would improve the accuracy significantly).

![image](https://github.com/jspooons/Motorway_Cars_Detector/assets/25199093/24b3b76b-a976-40dd-9bd2-b4ca3db8f827)
