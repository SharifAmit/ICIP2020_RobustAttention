# ICIP2020_RobustAttention
This code is part of the supplementary materials for the IEEE ICIP 2020 for our paper Improving robustness using Joint Attention network for Optical Coherence Tomography Images . The paper has since been accpeted to IEEE ICIP 2020 and will be preseneted in October 2020.

### Arxiv Pre-print
```
https://arxiv.org/abs/2005.08094
```

# Citation 
```
@article{kamran2020improving,
  title={Improving Robustness using Joint Attention Network For Detecting Retinal Degeneration From Optical Coherence Tomography Images},
  author={Kamran, Sharif Amit and Tavakkoli, Alireza and Zuckerbrod, Stewart Lee},
  journal={arXiv preprint arXiv:2005.08094},
  year={2020}
}
```

## Pre-requisite
- Ubuntu 18.04 / Windows 7 or later
- NVIDIA Graphics card

## Installation Instruction for Ubuntu
- Download and Install [Nvidia Drivers](https://www.nvidia.com/Download/driverResults.aspx/142567/en-us)
- Download and Install via Runfile [Nvidia Cuda Toolkit 9.0](https://developer.nvidia.com/cuda-10.0-download-archive?target_os=Linux&target_arch=x86_64&target_distro=Ubuntu&target_version=1804&target_type=runfilelocal)
- Download and Install [Nvidia CuDNN 7.6.5 or later](https://developer.nvidia.com/rdp/cudnn-archive)
- Install Pip3 and Python3 enviornment
```
sudo apt-get install pip3 python3-dev
```
- Install Tensorflow-Gpu version-2.0.0 and Keras version-2.3.1
```
sudo pip3 install tensorflow-gpu==2.0.0
sudo pip3 install keras==2.3.1
