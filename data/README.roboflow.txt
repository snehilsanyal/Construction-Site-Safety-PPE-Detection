
Construction Site Safety - v28 YOLOv5s
==============================

This dataset was exported via roboflow.com on February 1, 2023 at 4:08 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 2801 images.
Construction are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 20 percent of the image
* Random rotation of between -12 and +12 degrees
* Random shear of between -2° to +2° horizontally and -2° to +2° vertically
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -20 and +20 percent
* Random Gaussian blur of between 0 and 0.5 pixels


