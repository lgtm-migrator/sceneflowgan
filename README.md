
<!---
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/github/ravikt/sceneflowgan?style=plastic)](https://lgtm.com/projects/g/ravikt/sceneflowgan/)
--->

# SceneFlowGAN

[![License: MIT](https://img.shields.io/github/license/ravikt/sceneflowgan?style=plastic)](https://github.com/ravikt/sceneflowgan/blob/master/LICENSE)

This repository contains Keras implementation of our paper 

A Conditional Adversarial Network for Scene Flow Estimation (RO-MAN 2019)

[Ravi Kumar Thakur](https://ravikt.github.io/) and [Snehasis Mukherjee](https://sites.google.com/a/iiits.in/snehasis-mukherjee/)

## Abstract

<p style="text-align: justify">
The problem of Scene flow estimation in depth videos has been attracting attention of researchers of robot vision, due to its potential application in various areas of robotics. The conventional scene flow methods are difficult to use in reallife applications due to their long computational overhead. We propose a conditional adversarial network SceneFlowGAN for scene flow estimation. The proposed SceneFlowGAN uses loss function at two ends: both generator and descriptor ends. The proposed network is the first attempt to estimate scene flow using generative adversarial networks, and is able to estimate both the optical flow and disparity from the input stereo images simultaneously. The proposed method is experimented on a large RGB-D benchmark sceneflow dataset
</p> 

<img src="misc/SceneFlowGAN.jpg" width="600">

## Requirements

The code has been tested on Ubuntu 16.04 with CUDA 9.0. Python2 and Keras are required. Relevant python libraries can installed (inside virtual environment) using: 
```bash
pip3 install -r requirements.txt
```
Alternatively, a docker image can be created for running SceneFlowGAN inside a container. All the dependencies are included in the Dockerfile. 

## Acknowledgement

We would like to thank [Soumen Ghosh](https://sites.google.com/site/soumenca/) and [Shiv Ram Dubey](https://sites.google.com/site/shivram1987/) for providing feedback and insightful discussion. The work was supported by Department of Science and Technology, Government of India under Project ECR/2016/00652.

## Reference

Please use the following for citation purpose
```bibtex
@inproceedings{thakur2019conditional,
  title={A conditional adversarial network for scene flow estimation},
  author={Thakur, Ravi Kumar and Mukherjee, Snehasis},
  booktitle={2019 28th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)},
  pages={1--6},
  year={2019},
  organization={IEEE}
}
```
## Note

In case of difficulty in running the code, please post your question by filing an issue. To suggest any improvement to make the code more readable or optimized, open a pull request. 

