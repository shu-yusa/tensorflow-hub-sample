# Tensorflow Hub Sample
This script performs transfer learning based on Inception-v3 model.
Inception-v3 model is imported via Tensorflow Hub.

## Set up
```bash
virtualenv env
source env/bin/activate
pip install "tensorflow>=1.7.0"
pip install tensorflow-hub
```

## Usage
```bash
# Specify directory to cache modules
export TFHUB_CACHE_DIR=/tmp/my_module_cache
python inceptionv3.py
```

## Tensorboard
Log files are output in `/tmp/convnet`. You can check the result with `tensorboard`.
```bash
tensorboard --logdir=/tmp/convnet
```
