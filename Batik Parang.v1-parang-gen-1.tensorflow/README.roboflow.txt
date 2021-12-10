
Batik Parang - v1 Parang Gen-1
==============================

This dataset was exported via roboflow.ai on December 10, 2021 at 4:06 AM GMT

It includes 179 images.
Batik are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 200x200 (Stretch)
* Grayscale (CRT phosphor)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise
* Random brigthness adjustment of between -38 and +38 percent
* Random Gaussian blur of between 0 and 1 pixels


