# :books: CommonLit-Readability-Prize-Project
Project for Machine Learning exam 


##  :pencil: Table of contents
* [Description](#description)
* [How to use](#how-to-use)
* [Setup](#setup)
* [Technologies](#technologies)
* [License](#license)


## :pushpin: Description <a name="description"/>

The description below is taken from Kaggle competition [page](https://www.kaggle.com/c/commonlitreadabilityprize)

CommonLit, Inc., is a nonprofit education technology organization serving over 20 million teachers and students with free digital reading and writing lessons for grades 3-12. Together with Georgia State University, an R1 public research university in Atlanta, they are challenging Kagglers to improve readability rating methods.

In this competition, you’ll build algorithms to rate the complexity of reading passages for grade 3-12 classroom use. To accomplish this, you'll pair your machine learning skills with a dataset that includes readers from a wide variety of age groups and a large collection of texts taken from various domains. Winning models will be sure to incorporate text cohesion and semantics. 


## :man_technologist: How to use <a name="how-to-use"/>
In order to use this project, you have to follow passages written in [setup](#setup) and then it's recommended to change runtime in Runtime -> Change runtime modifying None in GPU. The project is divided in different section, one for all the step (libraries import, dataset preprocessing ecc...). 





## :gear: Setup <a name="setup"/>
To run this project, you can use Google Colab and upload the file, here is the [link](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index).
For this project we have used Google Drive to store dataset, so in order to run it properly you have to download dataset from Kaggle competition at this [page](https://www.kaggle.com/c/commonlitreadabilityprize/data) and then link your own content drive. 

We have also used another dataset which is AoA (Age-of-acquisition), this is the [website](http://crr.ugent.be/archives/806) and you download it [here](http://crr.ugent.be/papers/AoA_51715_words.zip).

## :computer: Technologies <a name="technologies"/>
Project is created with:
* Google Colab or Anaconda (for a local computation)
* Python
* Tensorflow
* Keras
* Sklearn
* XGBoost

## :balance_scale: License <a name="license"/>
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details
