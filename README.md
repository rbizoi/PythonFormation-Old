# Formation Python 

<img src="https://github.com/rbizoi/PythonFormation/blob/main/images/python-image-logo-940x530.jpeg" width="512">

# Installation 
https://www.anaconda.com/download

```
conda activate root
conda info --envs
conda update -n base -c defaults conda
python -m pip install --upgrade pip
conda install scikit-learn-intelex

conda remove -n spark3 --all -y

conda create -n spark3 python==3.10 pyspark ipython ipython-sql jupyter notebook numpy pandas pyarrow scikit-image scikit-learn scikit-learn-intelex seaborn tifffile portpicker  biopython flatbuffers  redis colour pydot pygraphviz pyyaml imgaug tifffile imagecodecs lightgbm xgboost -y
conda activate spark3

pip install opencv-python kaggle pydot pydicom dash dash-bootstrap-components dash-core-components dash-html-components dash-table dash-draggable dash-cytoscape dash_daq Pillow jupyter_dash imagecorruptions imblearn

pip install SQLAlchemy==1.4.39 cx_Oracle sql
pip uninstall matplotlib seaborn
pip install matplotlib seaborn

```


