# Choroid plexus lipid storage paper
This repository contains the code that accompanies the journal article "__" published in __. Specifically we include Jupyter notebooks to reproduce whole slide image processing, and training of deep learning models. The available code is provided as-is, and does not constitute a full-fledged software package for analysis. 
### System Requirments
This code repository was developed on Ubuntu 20. Hardware requirements for running this code includes a CUDA-compatible GPU. This code has been tested with a Nvidia RTX 3090 GPU. 
Software requirments include the installation of  NVIDIA-Docker. All code was tested on Ubuntu 20.04 LTS.
### Running environment
All code was run using a modified docker image. Running a docker container using this image ensures the code uses the correct system and Python packages. To setup the environment and follow the instructions at https://github.com/peterchang77/install and use the "gpu-full" docker image. After starting the docker container, install additional packages using the provided script (docker-additional-packages) before starting the Jupyterhub server.
