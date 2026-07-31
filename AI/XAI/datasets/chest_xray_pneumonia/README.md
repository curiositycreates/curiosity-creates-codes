# Sample Chest X-ray Images

This directory contains sample chest X-ray images used for the Grad-CAM demonstration in this repository.

The images are a small subset of the publicly available dataset:

**Chest X-Ray Images (Pneumonia)**
Dataset source:
https://huggingface.co/datasets/hf-vision/chest-xray-pneumonia

Original dataset publication:

Kermany, D., Zhang, K., & Goldbaum, M.
"Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification"
Mendeley Data, V2, 2018.
https://doi.org/10.17632/rscbjbr9sj.2

## License

The original dataset is distributed under the terms of the:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

License:
https://creativecommons.org/licenses/by/4.0/

The images included in this directory are redistributed according to the terms of the CC BY 4.0 license.

When using these images, please provide appropriate attribution to the original dataset authors and source.

## Attribution

If you reuse these images, please cite:

> Kermany, D., Zhang, K., & Goldbaum, M. (2018).
> Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification.
> Mendeley Data, V2. https://doi.org/10.17632/rscbjbr9sj.2

Dataset mirror:
https://huggingface.co/datasets/hf-vision/chest-xray-pneumonia

## Contents

The directory contains only a small number of example images used for demonstrating:

* Image classification using a ResNet-based model
* Grad-CAM visualization
* Interpretation of model predictions

The complete dataset is **not included** in this repository.

Users who need the full dataset should obtain it from the original distribution source.

## Modification

The images in this repository are used as input images for Grad-CAM visualization.

The generated Grad-CAM heatmaps are derived outputs created by applying an explainable AI method to these images.
