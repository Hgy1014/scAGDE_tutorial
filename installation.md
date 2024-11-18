# Installation


## System Requirements
### Hardware requirements
`scAGDE` package requires only a standard computer with enough RAM to support the in-memory operations.

### Software requirements
#### OS Requirements
This package is supported for *Linux*. The package has been tested on the following systems:
+ Linux: Ubuntu 18.04

#### Python Dependencies
`scAGDE` mainly depends on the Python scientific stack.
```
numpy
scipy
torch
scikit-learn
pandas
scanpy
anndata
rpy2
```
For specific setting, please see <a href="requirements.txt">requirements.text</a>.
#### R Dependencies
We need your environment to have R and `mclust` package installed.
## Installation Guide:
You can create an environment to run scAGDE without any problems by following the code below:
```
conda create -n scagde python=3.9.13
conda activate scagde
pip install torch==2.0.1
pip install numpy==1.23.5
pip install rpy2==3.5.13
pip install scanpy==1.9.3
pip install matplotlib==3.5.0
conda install r-mclust
pip install scAGDE
```
