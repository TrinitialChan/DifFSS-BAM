## DifFSS: Diffusion Model for Few-Shot Semantic Segmentation

This is the implementation of the DifFSS method on BAM (DifFSS-BAM) in paper "DifFSS: Diffusion Model for Few-Shot Semantic Segmentation".

For more information, Please refer to the the paper on [[arXiv](https://arxiv.org/abs/2307.00773)].

## :hammer_and_wrench: Getting Started with DifFSS-BAM

### 1. Preparation of environment and dataset

Please configure the conda environment and prepare the required datasets and base model weights as described in the [readme](https://github.com/chunbolang/BAM) file of the original BAM model.

### 2. Preparation of auxiliary support images

Please refer to [ControlNet4FSS](https://github.com/TrinitialChan/ControlNet4FSS) for the pre-generation of auxiliary supoort.

### 3. Traing

Once the pre-generated auxiliary support images are ready, you can start training the model by modifying the aux_data_dir field in the config file.


