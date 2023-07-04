# Deep Learning Nanodegree - project2

## by (Lara Alfayyadh)

### I completed this project as part of Udacity's Deep Learning Nanodegree.



## Landmark Classification

> This project develops convolutional neural networks (CNNs) for identifying landmarks on social media images. The project explores 2 methodologies: building a neural network "from scratch" and building a neural network using transfer learning (based on the VGG16 pre-trained model).


## Problem

### Overview
> Images are being uploaded to social media platforms everyday. During upload, these services can automatically tag the image with its location based on the image metadata (such as GPS coordinates).
> However, when the image does not contain GPS data, an alternate method to pinpoint the location where the photo was taken is to identify a recognizable landmark in the picture. This can be performed with a CNN.

### Requirements
> * Design 2 CNNs to classify an image based on a landmark in this image.
>    * 1 CNN "from scratch".
>    * 1 CNN using transfer learning.
> * Select the best CNN (target accuracy > 60%).
> * Create a simple interface for others to run the best CNN developed above.


## Input Data
> CNNs in this project are trained using a dataset of landmark images provided by Udacity.

> This dataset contains about 6000 images divided into 50 categories. Image category ID/names are stored in file categories.json.

> Note that the dataset used in this project is a subset of the Google Landmark Dataset v2.
