# Pretrained Weights for Medical Radiography

Medical imaging datasets come in all shapes and sizes. Transfer learning is useful when data are limited. Most commonly, ImageNet-pretrained weights are used. This repo offers an alternative, specifically for medical radiographs (i.e., X-rays). Weights were initialized with ImageNet-pretrained weights and further trained on over 200,000 radiographs across all body parts to predict both the body part region and a priority score (normal, routine, acute) determined by a radiologist.

Currently, only PyTorch weights are provided. TensorFlow/Keras to follow. 

## Requirements
- PyTorch 1.0 or later
- pretrainedmodels (https://github.com/Cadene/pretrainedmodels)

