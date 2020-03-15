# Python-CUDA

Nvidia CUDA Linux Container Image Sources with a full Python base.

These Dockerfiles will build CUDA and cuDNN images with a full Python base to allow installation and compilation of
other Python code into the image. The Python base image uses Debian Buster rather than the the default Nvidia images
which are based upon Ubuntu 18.04

These files are based upon nvidia/cuda Ubuntu images, the full source of which can be found here:
https://gitlab.com/nvidia/container-images/cuda/-/tree/master

## How to build images

Requires Docker and docker-compose installed.

`docker-compose -f build.yml build`
