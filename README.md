# Medical-Record-Linkage-Ensemble Paper Reproduction

This repository contains two notebooks one for each dataset (FEBRL and ePBRN) and utilizes the code provided by the authors of the original paper, [Statistical supervised meta-ensemble algorithm for medical record linkage](https://www.sciencedirect.com/science/article/pii/S1532046419301388?via%3D), to reproduce its results and claims and also builds on top of for additional ablations and experiments.


>Authors of the original paper: 
> + Kha Vo <kha.vo@unsw.edu.au>,
> + Jitendra Jonnagaddala <jitendra.jonnagaddala@unsw.edu.au>,
> + Siaw-Teng Liaw <siaw@unsw.edu.au>.

> Resources used to reproduce results:
>
> Original Code provided by authors:
> 
> Kha Vo and Jitendra Jonnagaddala and Siaw-Teng Liaw. (2019). Medical-Record-Linkage-Ensemble. Retrieved from https://github.com/ePBRN/Medical-Record-Linkage-Ensemble. Paper: "Statistical supervised meta-ensemble algorithm for data linkage"

> Original Paper:
> 
>Kha Vo, Jitendra Jonnagaddala, Siaw-Teng Liaw, Statistical supervised meta-
ensemble algorithm for medical record linkage, Journal of Biomedical Informatics, Volume 95, 2019, 103220, ISSN 1532-0464, https://doi.org/10.1016/j.jbi.2019.103220.


## Requirements

All code is run sucessfully in Google Colab Pro environment with Python 3.6. You will need a Google Colab Pro Account to run the notebooks on. Google Colab already comes with a lot of default ML packages installed and does not require additional installation. The only package used by the authors that is not installed in Google Colab Pro is [`record_linkage`](https://recordlinkage.readthedocs.io/en/latest/about.html). There is a cell in each runbook that when it is ran in Google Colab Pro, it will install the package.

## Training & Evaluation

For training and evaluating the models, there are dedicated cells in each notebook that have the set hyperparameters and does not require any additional setup or commands, except just running the cell in Google Colab Pro.


## Results

The following baseline performance results are from the reproduction of the original paper, and not the original results as stated by the authors:


### FEBRN dataset (Source A):

| Model name  | Precision       | Recall         | F-Score
| ----------- |---------------- | -------------- | ------------|
| SVM         |     98.72%      |      99.63%    |    99.18%   |
| NN          |     96.96%      |      99.43%    |    99.19%   |
| LR          |     97.64%      |      99.63%    |    99.62%   |

### FEBRN dataset (Source B):

| Model name  | Precision       | Recall         | F-Score
| ----------- |---------------- | -------------- | ------------|
| SVM         |     31.78%      |      98.61%    |    48.07%   |
| NN          |     69.20%      |      96.46%    |    80.59%   |
| LR          |     59.06%      |      96.84%    |    73.37%   |

