# Medical-Record-Linkage-Ensemble Paper Reproduction

Course: Deep Learning for Healthcare
by Gargi Deb

This repo contains two notebooks one for each dataset (FEBRL and ePBRN) and utilizes the code provided by the authors of the original paper to reproduce its results and claims and also build on top of for additional ablations and experiments.

Authors of the original paper: 
Kha Vo <kha.vo@unsw.edu.au>,
Jitendra Jonnagaddala <jitendra.jonnagaddala@unsw.edu.au>,
Siaw-Teng Liaw <siaw@unsw.edu.au>.

Resources:
+ Github Resource:
Kha Vo and Jitendra Jonnagaddala and Siaw-Teng Liaw. (2019). Medical-Record-Linkage-Ensemble. Retrieved from https://github.com/ePBRN/Medical-Record-Linkage-Ensemble. Paper: "Statistical supervised meta-ensemble algorithm for data linkage"

+ Original Paper:
Kha Vo, Jitendra Jonnagaddala, Siaw-Teng Liaw, Statistical supervised meta-
ensemble algorithm for medical record linkage, Journal of Biomedical Informatics, Volume 95, 2019, 103220, ISSN 1532-0464, https://doi.org/10.1016/j.jbi.2019.103220.

+ Additional Resources:
++ Ahmad Anis. Pytorch LSTM: The Definitive Guide. Mar. 2022. URL: https://cnvrg.io/pytorch-lstm/.

++ Improving LBFGS algorithm in pytorch. URL: http://sagecal.sourceforge.net/pytorch/index.html#:̃:text=Closure,documentation%5C%2C%5C%20with%5C%20a%5C%20small%5C%20modification.


All code is run sucessfully in Google Colab Pro environment with Python 3.6.

Packages used:
`numpy`
`pandas` 
`sklearn`
`torch`
`recordlinkage`

1. Create a Google Colab Pro Account and upload the two files: `FEBRL(Source_A)_code.ipynb` and `ePBRN(Source_B)_code.ipynb` to Google Drive to then be accessed and run in Google Colab Pro environment.

2. Obtain datasets required to run code. Download and save `febrl3_UNSW.csv`, `febrl3_UNSW.csv`, `ePBRN_D_dup.csv`, and `ePBRN_F_dup.csv` from the repo of the original paper found here https://github.com/ePBRN/Medical-Record-Linkage-Ensemble. These four files will then need to be uploaded as part of running the code.

3. Run each cell for a notebook one a time, and follow the instructions (if any) above cell. The results for the models will be printed below the cell.

