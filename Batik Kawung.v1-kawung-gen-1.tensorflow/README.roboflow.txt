
Batik Kawung - v1 Kawung gen-1
==============================

This dataset was exported via roboflow.ai on December 10, 2021 at 1:02 PM GMT

It includes 640 images.
Batik are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 200x200 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 41 percent of the image
* Random rotation of between -18 and +18 degrees
* Random brigthness adjustment of between -30 and +30 percent
* Random Gaussian blur of between 0 and 0.75 pixels
* Salt and pepper noise was applied to 5 percent of pixels


