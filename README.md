# 3D MRI Brain Tumor Segmentation Using Autoencoder Regularization
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-mri-brain-tumor-segmentation-using/brain-tumor-segmentation-brats-2018)](https://paperswithcode.com/sota/brain-tumor-segmentation-brats-2018?p=3d-mri-brain-tumor-segmentation-using)
![The model architecture](https://suyogjadhav.com/images/misc/brats2018_sota_model.png)
<center><b>The Model Architecture</b><br />Source: https://arxiv.org/pdf/1810.11654.pdf</center>

Implementation of the paper titled 3D MRI brain tumor segmentation using autoencoder regularization by Myronenko (https://arxiv.org/abs/1810.11654). The author (team name: **NVDLMED**) was ranked #1 on the [BRATS 2018](https://www.med.upenn.edu/sbia/brats2018/) leaderboard.

# Progress
Currently, the complete Encoder and the Upper branch of decoder (Ground Truth) have been implemented completely.

# TODO
- The lower branch (VAE part) of the decoder
- The custom loss function that the author used. (L = L<sub>dice</sub> + 0.1 ∗ L<sub>L2</sub> + 0.1 ∗ L<sub>KL</sub> )
I will soon modularize the code and create a single python script with a fully customizable keras model.
