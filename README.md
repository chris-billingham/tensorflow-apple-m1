# Using Tensorflow Metal on Apple Mac M1

### Install the Python stuff you need

`cd Downloads && curl -O https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh`

`chmod +x ~/Downloads/Miniforge3-MacOSX-arm64.sh`

`sh ~/Downloads/Miniforge3-MacOSX-arm64.sh`

`source ~/miniforge3/bin/activate`

`conda install -c apple tensorflow-deps`

`python -m pip install tensorflow-macos`

`python -m pip install tensorflow-metal`

`conda install -y pandas matplotlib scikit-learn jupyterlab`

### Things to do in RStudio

Add this to .Renviron `RETICULATE_PYTHON='~/miniforge3/bin/python3'`
