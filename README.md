# autoencoder-imputation-xyonix-blog
Exploring the Power of Autoencoders for Data Imputation.

# installation
```
# 1. Create a conda environment with Python 3.10
conda create -n xyonix_autoencoder python=3.10

# 2. Activate the environment
conda activate xyonix_autoencoder

# 3. Install essential Python packages via conda
conda install -c conda-forge jupyter ipykernel numpy pandas joblib scikit-learn matplotlib seaborn

#    Note: The `-c conda-forge` ensures we get up-to-date packages from the conda-forge channel.

# 4. Install TensorFlow
#    - On most Linux/Windows with Python 3.10:
pip install tensorflow

#    - On M1/M2 Macs (Apple Silicon), install these instead:
# pip install tensorflow-macos tensorflow-metal

# 5. Register the environment’s kernel with Jupyter
python -m ipykernel install --user --name xyonix_autoencoder

# 6. Launch Jupyter Notebook
jupyter notebook
```

Once the Jupyter notebook navigator loads:

1. Select `autoencoder_imputation.ipynb` to open notebook 
2. Select `Kernel >> Change kernel >> xyonix_autoencoder` from pull-down menu

# notebook

The [Jupyter Notebook](https://github.com/xyonix/autoencoder-modeling-blog/blob/master/autoencoder_imputation.ipynb) 
corresponds to the XYONIX article, [Filling the Gaps: AI-Powered Data Imputation with Autoencoders on Housing Data](https://www.xyonix.com/blog/filling-the-gaps-ai-powered-data-imputation-with-autoencoders-on-housing-data). 
Run the cells in the notebook in order to reproduce the plots shown in the article.

```