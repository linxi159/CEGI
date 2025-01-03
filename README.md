# CEGI
CEGI: Causally explainable gene identification method for unveiling developmental signatures in human prefrontal cortex
![](https://github.com/linxi159/CEGI/blob/main/figures/Figure_1.tif) 

## Description of each directory
data: the preprocessed data from human prefrontal cortex scRNA-seq data in GEO.

results: the final results for the BN.

figures: the plot for CEGI.


## How to setup

* Python (3.6 or later)

* numpy

* sklearn

* pytorch

* NVIDIA GPU + CUDA 11.50 + CuDNN v7.1

* scipy


## Quick example to use CEGI
```
* train and test the model:

* the implementation of interpretable gene signature identification between P5 and P6 development stages in human PFC
python step2_train_1_P5toP6.py

* the implementation of interpretable gene signature identification between P6 and P7 development stages in human PFC
python step3_train_2_P6toP7.py

```
