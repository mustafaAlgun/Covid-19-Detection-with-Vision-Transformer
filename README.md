<br/>
<p align="center">
  <h3 align="center">Covid-19 Detection with Vision Transformer From Scratch</h3>

  <p align="center">
    EDA, Data Augmentation, Neural Network training, and Result Analysis in just one Jupyter Notebook
    <br/>
    <br/>
    <a href="https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer">View Demo</a>
    .
    <a href="https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/issues">Report Bug</a>
    .
    <a href="https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/issues">Request Feature</a>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer?color=dark-green) ![Forks](https://img.shields.io/github/forks/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer?style=social) ![Stargazers](https://img.shields.io/github/stars/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer?style=social) ![Issues](https://img.shields.io/github/issues/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer) ![License](https://img.shields.io/github/license/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Vision_Transformer.gif/450px-Vision_Transformer.gif)

In this project, 

* We'll analyze a dataset (check out the link below), see if there's any imbalance, visualize the data and look at their properties.
"https://data.mendeley.com/datasets/jctsfj2sfn/1"
* We'll create train,test, and validation sets for our model with scikit-learn tools.
"https://scikit-learn.org/stable/"
* We'll utilize Keras library and its methods extensively to convert the data into tensors to be able to work with them efficiently.(check out the links below for more info).
"https://www.tensorflow.org/"
"https://keras.io/"
"https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator"
* We'll create ViT model from scratch for image classification following the paper "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale" (check the Acknowledgements section).
A huge thanks to "https://github.com/givkashi/" for the template of the model.
* After successfully training the model, we'll analyze the running time & memory occupation(complexity).
* We'll investigate the accuracy and loss of the model.
* We'll create a confusion matrix and visualize it.
* We'll create a classification report " PRECISION, RECALL & F1-SCORE" and visualize them on the data.
* Then, we'll train the model using "Stratified K-Fold" as many competitors in Kaggle do in competitions as see if we get any improvements on our results (check out the link below).
"https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.StratifiedKFold.html"
* [Not done yet] We'll try to implement "GRAD Cam" to understand on which parts of the images out attention model focused for prediction (check the Acknowledgements section).


## Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

## Getting Started

This Jupyter Notebook was written in Python & Tensorflow. You can directly download the notebook and run it locally, or you can upload it on Google Collabs and run there (I recommend GPU usage for faster training time). <br />
OR  <br />
**[Recommended]** You can go to [my Kaggle profile](https://www.kaggle.com/mustafaalgun/covid-detection-with-vision-transformer) and easily copy & edit it. 
To get a local copy up and running follow these simple example steps.



### Installation

Clone the repo

```sh
git clone https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer.git
```
### Dataset

Dataset can be downloaded from [this link](https://data.mendeley.com/datasets/jctsfj2sfn/1).

## Usage

This is a walk-through Jupyter Notebook. Therefore, following the steps and reading comments will be more than enough for you to replicate the results :) Mind you, you may need to change the paths of files according to where they are in your local machine. Here are some screenshots from the code & results.


![Screen Shot](https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/blob/main/Screenshots/gif.gif?raw=true)


## Roadmap

See the [open issues](https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request



## Authors

* **Mustafa Algun** - *Master's Student at University of Padua*

## Acknowledgements

* [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale, Alexey Dosovitskiy](https://arxiv.org/abs/2010.11929)
* [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization, Ramprasaath R.](https://arxiv.org/abs/1610.02391?source=post_page---------------------------)
* [Template ViT Model we built our model on](https://github.com/givkashi/Vision-Transformer-from-scratch)
