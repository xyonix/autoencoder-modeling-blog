# autoencoder-imputation-xyonix-blog
Exploring the Power of Autoencoders for Data Imputation.

# installation
```
# 1. Create and activate a new virtual environment
python3 -m venv xyonix_autoencoder
source xyonix_autoencoder/bin/activate

# 2. Upgrade pip, setuptools, wheel
pip install --upgrade pip setuptools wheel

# 3. Install Jupyter + minimal required packages
pip install jupyter ipykernel
pip install numpy pandas joblib scikit-learn matplotlib seaborn
pip install tensorflow

# 4. Register a new kernel for this environment
python -m ipykernel install --user --name xyonix_autoencoder

# 5. Launch Jupyter Notebook
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