Steps to setup environment 

1:conda create -n pymc3_env python=3.10

2:conda activate pymc3_env

3:conda install pymc3

Installing libraries 
4:conda install scikit-learn
conda install seaborn
conda install mkl
conda install blackjax

To access env in Jupyter notebook 
conda install ipykernel
python -m ipykernel install --user --name=<pymc3_env> --display-name "Python (pymc3_env)"
