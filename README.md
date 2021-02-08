## Gradient-based Class Activation Mapping (Grad-CAM) for fluid flow regression problems

This repository contains the simple source codes of "Generalization techniques of neural networks for fluid flow estimation," arXiv:2011.11911 [phys.flu-dyn.].

A CNN-MLP type neural network is trained to estimate drag force coefficient of cylinder wake from its vorticity field.
The Grad-CAM map indicates the region around a cylinder surface is highly responsible for the estimation.

Vorticity field             |  Grad-CAM map
:-------------------------:|:-------------------------:
![alt text](https://github.com//Masaki-Morimoto/Grad-CAM_for_fluid-flows/blob/images/vorticity.png?raw=true)  |  ![alt text](https://github.com//Masaki-Morimoto/Grad-CAM_for_fluid-flows/blob/images/grad-cam.png?raw=true)

<div style="text-align: center;">Vorticity field of a cylinder wake (input data) and its Grad-CAM map of the force coefficient estimation.</div>

## Information

Author: Masaki Morimoto ([Keio University](https://kflab.jp/ja/))

This repository contains

Grad-CAM_for_CDprediction_cylinder.ipynb

For citations, please use the reference below:

M. Morimoto, K. Fukami, K. Zhang, and K. Fukagata "Generalization techniques of neural networks for fluid flow estimation," arXiv:2011.11911 (2020).
Authors provide no guarantees for this code.
Use as-is and for academic research use only; no commercial use allowed without permission.
The code is written for educational clarity and not for speed.

## Requirements
- Python 3.X
- keras
- tensorflow
- numpy
- pandas
- matplotlib
- cv2
- tqdm
