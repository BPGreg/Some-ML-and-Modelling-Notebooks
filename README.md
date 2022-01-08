# Some-ML and Modelling Notebooks

This repository contains several notebooks implementing and testing machine learning algorithms, techniques, and some modelling projects.

## List of files

### `GAN_for_anime_faces.ipynb`
 
In this notebook, we implement a **DCGAN to generate faces in a manga-like style**. For this project, we used [this dataset from WANG Yaohui](https://gitlab.inria.fr/yaowang/gan_class_images.git). This notebook uses PyTorch as its ML framework.

### `classification-on-plantnet.ipynb` ⭐

This notebook comes from a Kaggle competition (using [this subset](https://gitlab.inria.fr/cgarcin/plantnet_dataset) of the [Plantnet dataset](https://plantnet.org/en/)). This notebook comprehensively goes through the whole process of building a **classifier on image data**, from custom datasets, samplers, models, etc. Model-wise, this notebook uses **CNNs, homemade residual networks, and a fine-tuned ResNet152**. This notebook is extensively commentated, and documents all of the tested configurations and their scores during the competition. This notebook uses PyTorch as its ML framework.

### `Chocolate Bar Rating Using NNs`

This notebook comes from a Kaggle Challeng: the prediction of a rating of a chocolate bar given some features of this one, with a neural network.
This code uses the API [keras for R language](https://tensorflow.rstudio.com/guide/keras/) (this kaggle challenge imposed the R language).

### `Prostate Cancer Modelling`

This notebook comes from a project where we were asked to model the propagation of a cancer in a prostate.

Note : Some of these notebooks are the products of uni labs or projects, and may thus have a few obscure headers (for example, when they reference exercise questions or subject codes).
