<br/>
<img height="200" alt="HCMUT" src="https://upload.wikimedia.org/wikipedia/commons/d/de/HCMUT_official_logo.png" />
<br/>

# CVL: Computer Vision Self-Learning Project

CVL is a small multi-project that has been done by two members.
Our goal is to experience various small projects with public datasets to learn computer vision.

Our present research-pipeline is: simple image classifier - advanced image classifier - data augmentation - transfer learning - image detection - semantic segmentation.

Almost all of the projects are run on Google Colab / Jupyter Notebook.

## Models

  File | Model | Parameters | Training data | Training time | Evaluation
---|---|---|---|---|---
`Dogs_and_cats_classification`/`dogs_and_cats.ipynb` | VGG19 | 20M | [Kaggle Dataset](https://www.kaggle.com/competitions/dog-vs-cat-classification) | 30 minutes on GPU Tesla K80 |  98.6 % F1 
`Dogs_and_cats_classification`/`kaggle_cat_dog.ipynb` | InceptionV3/Custom Model | 20M | [Kaggle Dataset](https://www.kaggle.com/competitions/dog-vs-cat-classification) | CPU |  96.54/81.04 % F1 

## Dog and Cat Classifications
It's a Kaggle competition on a small dataset with 2 classes: Dogs and Cats.

Our task is simply training the model classifying between a dog and a cat in each image. 
The dataset is good to practice and compare the different SOTA backbones of Computer Vision such as:
- Transformer
- CNN: EfficientNet, ConvNeXt, ResNet, ResNext, MobileNet, AlexNet, InceptionNet, DenseNet,…
- Other architecture

Details can be found on: \href = [Dog vs Cat classification]("https://www.kaggle.com/competitions/dog-vs-cat-classification")

Because the dataset is quite small and simple structure, so transfer learning tends to obtain a very good results, don't even need fine-tuning or a large number of epochs.

<img height="200" alt="HCMUT" src="https://github.com/electrodrago/computer-visit/blob/main/result/dogncat.png" />

