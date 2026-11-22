# Physics-Informed Neural Networks with a Convolutional Encoder for the KdV Equation

This repository contains the official PyTorch implementation for the paper:

**"Physics-Informed Neural Networks with a Convolutional Encoder for the KdV Equation under Sparse and Noisy Observations"**
*Authors: Jibrin Sale Yusuf, Aliyu Isa Aliyu, and Ado Balili*

## Overview
This code implements a hybrid CNN-PINN architecture to reconstruct Korteweg-de Vries (KdV) solitons from sparse and noisy observations. The convolutional encoder maps sparse observations to a latent field, and the fully connected PINN decoder enforces the PDE residual, initial conditions, and boundary conditions. 

## Repository Structure
*   `CNN_PINN_KdV_Training.ipynb`: The main Jupyter Notebook containing the data generation, CNN Encoder and PINN Decoder architecture, training loop, and evaluation.
*   `requirements.txt`: List of required Python packages.

## Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/jsyusuf/CNN-PINN-KdV.git
   cd CNN-PINN-KdV
```
2. Install the dependencies
```bash
pip install -r requirements.txt
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `CNN_PINN_KdV_Training.ipynb` and run the cells sequentially to reproduce the results. 
*(Note: A CUDA-enabled GPU is highly recommended for training).*
## Citation
If you use this code in your research, please cite our paper:

```bibtex
@article{yusuf2026cnnpinn,
  title={Physics-Informed Neural Networks with a Convolutional Encoder for the KdV Equation under Sparse and Noisy Observations},
  author={Yusuf, Jibrin Sale and Aliyu, Aliyu Isa and Balili, Ado},
  year={2026}
}
```
## License
This project is licensed under the MIT License.
