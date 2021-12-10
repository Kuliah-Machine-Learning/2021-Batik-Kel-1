
Batik Parang - v2 Parang Gen-2
==============================

This dataset was exported via roboflow.ai on December 10, 2021 at 4:12 AM GMT

It includes 167 images.
Batik are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 200x200 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise
* Random brigthness adjustment of between -38 and +38 percent
* Random Gaussian blur of between 0 and 1 pixels
* Salt and pepper noise was applied to 5 percent of pixels


