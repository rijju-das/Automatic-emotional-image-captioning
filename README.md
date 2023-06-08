# Automatic Image Captioning in facial emotion dataset

## Description

This is the code repo for UCD final year project: Automatic Image Captioning in facial emotion dataset

The project develops an appropriate model for images containing human faces that provides a more accurate and impact caption. 

The project aims to:
* Preparing a group of suitable data from dataset.
* Developing a model to generate new caption from the image.
* Developing a model to extract emotion from the human face.
* Developing a model to produce improved captions from caption and emotion generated.
* Evaluating and analysing the performance of the model.

For more details, please check the project report.


## Getting Started

### Prerequisites

No prerequisite required.

### Installation

1. Clone or download the repo
   ```sh
   git clone https://csgitlab.ucd.ie/nanwu/automatic-image-captioning-in-facial-emotion-dataset.git
   ```
2. Upload all files to [Google Colab](https://colab.research.google.com)
   
3. Run from Google Colab

### Train the model

Runs should follow the following order:
1. data-cleaning.ipynb

   Create flickr5k dataset folder from flickr8k

2. (optional) flickr5k-analysis.ipynb

   Only used for dataset analysis

3. image-feature.ipynb

   Create flickr5k_features.pkl storing image features in flickr5k folder

4. tokenize-caption.ipynb

   Create flickr5k_tokenizer.pkl storing caption tokenizer in flickr5k folder

5. image-captioning-model.ipynb

   Create flickr5k_model.h5 storing the model in flickr5k folder

### Use the model

Run:
1. emotion-and-evaluation.ipynb

   This script requires flickr5k_model.h5 and evaluation images

## Contact

Nan Wu - nan.wu1@ucdconnect.ie




