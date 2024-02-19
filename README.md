# Formation Python 

<img src="https://github.com/rbizoi/PythonFormation/blob/main/images/python-image-logo-940x530.jpeg" width="512">

# Installation 

## Anaconda 

<img src="https://github.com/rbizoi/PythonFormation/blob/main/images/anaconda.png" width="512">


https://www.anaconda.com/download

## Environnement Python

```
conda activate root
conda info --envs
conda update -n base -c defaults conda
python -m pip install --upgrade pip
conda install scikit-learn-intelex

conda remove -n cours --all -y

conda create -n cours python==3.10 ipython ipython-sql jupyter notebook numpy pandas pyarrow scikit-image scikit-learn scikit-learn-intelex seaborn tifffile portpicker  biopython flatbuffers colour pydot pygraphviz -y
conda activate cours
```


