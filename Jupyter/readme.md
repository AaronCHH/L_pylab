# Jupyter

## Update
```
conda update conda
conda update jupyter
conda update jupyter notebook
```

## Check config path
```
jupyter --path
```

## Customization path
```
[Anaconda Install Path]\Lib\site-packages\notebook\static\custom
```

## Check conda env
```
conda env list
```

## Check notebook kernel
```
jupyter kernelspec list
```

## nbetension
```
# conda
conda install -c conda-forge jupyter_contrib_nbextensions

# pip
pip install jupyter_contrib_nbextensions
# OR
pip install https://github.com/ipython-contrib/jupyter_contrib_nbextensions/tarball/master

# Install javascript and css files
jupyter contrib nbextension install [--user]
```
### Enabling/Disabling extensions　
```
jupyter nbextension enable [codefolding]/main
jupyter nbextension disable [codefolding]/main
```
* https://github.com/ipython-contrib/jupyter_contrib_nbextensions