# Installing Anaconda - Mac M1

###Installing Miniforge
- Install brew https://brew.sh/, or copy paste this command to your terminal `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- Install miniforge from brew: brew install miniforge
- Activate the environment: conda activate 

###Install Python: conda install python

### Installing TensorFlow
- `conda install -c apple tensorflow-deps`
- `pip install tensorflow-metal` to install Apple's Metal GPU APIs for TensorFlow
- `pip install tensorflow-macos` to install MacOS arm64 version of TensorFlow
- `pip install tensorflow-datasets pandas jupyterlab` to install other packages