# Optimal Transport Particle Filters

This repository is by Mohammad Al-Jarrah, [Bamdad Hosseini](https://bamdadhosseini.org/), [Amirhossein Taghvaei](https://www.aa.washington.edu/facultyfinder/amir-taghvaei) and contains the Pytorch source code to reproduce the experiments in our 2023 paper [Optimal Transport Particle Filters](https://arxiv.org/abs/2304.00392).

<p align="center">
<img src="/images/X.png" width="250" height="250"><img src="/images/XX.png" width="250" height="250"><img src="/images/XXX.png" width="250" height="250">
</p>

If you find this repository useful for your publication, please consider citing our paprt.
'''
@article{al2023optimal,
  title={Optimal Transport Particle Filters},
  author={Al-Jarrah, Mohammad and Hosseini, Bamdad and Taghvaei, Amirhossein},
  journal={arXiv preprint arXiv:2304.00392},
  year={2023}
}
'''

## Setup
* Python/numpy
* PyTorch

## Running the code and Regenerate data and figures.
1. Run the 'main.py' file to regenerate and save the date. There are multiple things you can change in the code:
  - The observation function 'h(x)', please use the desired observation function here.
  - The number of sumlations 'AVG_SIM', we used 100 simulations in our paper but you can change that to a smaller number to get faster results.
  - The number final number of iterations 'parameters['Final_Number_ITERATION']' 
  - Other parameter to choose like the noise level, the number of particle 'J',..., etc.
2. Use the file 'import_DATA.py' to import and plot all the desired figures. Note here, we will plot the 'mse' for both $\phi{x}=x$ and $\phi{x}=max(0,x)$.
  

