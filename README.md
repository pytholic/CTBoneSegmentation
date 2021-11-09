# CT Bone Segmentation
## Description
Segmenting `skull bone` in medical images (head CT scans of the patients). 

## Overview
We can use two approaches for the task. The first one is `Traditional Methods` and the second one is `Deep Learning`.

### Traditional Methods
These image processing methods basically separate out different parts of the images based on the **intensity values** of the pixels.
Some of the basic operations used are.

* Thresholding
* Windowing
* Morphology (Erosion, Dilation, Opening, etc.)
* Blurring
* Masking and so on.

### Deep Learning Methods
Deep learning-based methods require annotated datasets with `ground-truth` masks. We can use these maasks along with image datasets to train a deep neural network like `UNet` architecture. Such networks perform betetr than classical approaches nowadays and are `fully-automated`. However, deep learning-based methods usually require large datasets for training purpose.

## Current Approach
For now, to segment skull bone, we only focus on traditional methods. The reason for that is that bone intensity is usually very high compared to other parts of the image, so we can easily segment it using techniques like `thresholding` and other methods. However, we can still use deep learning for this task and make it fully automated. For now, that is in future goals and we will only use classical methods at the moment.
