# deep-photo-styletransfer
Code for paper "Deep Photo Style Transfer": [arXiv link coming soon]


# Setup
This code is based on torch. It has been tested on Ubuntu 14.04 LTS. 

Dependencies:
* [Torch](https://github.com/torch/torch7) (with [matio-ffi](https://github.com/soumith/matio-ffi.torch) and [loadcaffe](https://github.com/szagoruyko/loadcaffe))
* [Matlab](https://www.mathworks.com/)

CUDA backend:
* [CUDA](https://developer.nvidia.com/cuda-downloads)
* [cudnn](https://developer.nvidia.com/cudnn)

Download VGG-19:
```
sh models/download_models.sh
```


# Usage
To generate all results using the provided scripts, first in Matlab
```
run('gen_laplacian/gen_laplacian.m')
```
and then in Python
```
python gen_all.py
```
.


# Examples











