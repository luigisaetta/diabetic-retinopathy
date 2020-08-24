# Diabetic Retinopathy Detection (based on CNN)

Luigi Saetta, luigi.saetta@gmail.com

August 2020 (Asiago, Italy)

This repository contains the best code I have developed working on Kaggle (2015)
Diabetic Retinopathy Detection competition dataset

see: https://www.kaggle.com/c/diabetic-retinopathy-detection

I have:
* taken the dataset from Kaggle
* processed images and packed in TFRecords file, for fast training on GPU
* developed models based on TF 2.3, CNN (Efficient Net)

Best result obtained:
* images 512x512, circle-crop + gaussian blur
* EfficientNet 4
* Train accuracy: 0.865
* see also my (late) submission on Kaggle, best score is: **0.79369** (14 place over 660)

## Datasets

for access to datasets used, see Datasets page in the Wiki:

https://github.com/luigisaetta/diabetic-retinopathy/wiki/Datasets



