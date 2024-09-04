# Secure Task Offloading with Identity-Based Cryptography in Vehicular Twin Networks

This repository contains the code and resources for implementing secure task offloading management using lightweight Identity-Based Cryptographic (IBC) authentication in cloud-based 6G Vehicular Twin Networks (VTNs).

# Abstract

Task offloading in 6G vehicular networks ensures network efficiency as vehicles generate massive amounts of data. However, secure communication via authentication introduces significant computational and communication overhead, negatively affecting offloading efficiency and latency. This repository presents a unified framework integrating lightweight IBC authentication into task offloading within VTNs. Using Proximal Policy Optimization (PPO) in Deep Reinforcement Learning (DRL), our model optimizes offloading decisions to reduce latency and improve resource allocation. The framework is evaluated under various network sizes, task complexities, and transmission data rates. Results show that while IBC authentication can reduce offloading efficiency by up to 50%, increasing the transmission data rate improves performance by up to 63%, mitigating the efficiency loss caused by authentication overhead.

# Key Features:
- Optimize task offloading and resource allocation under varying network sizes and task complexities.
- Evaluate the impact of IBC authentication on offloading efficiency and latency.
- Implement PPO-based intelligent decision-making for authenticated task offloading.
- Assess performance improvements by adjusting transmission data rates, task sizes, and network sizes in the presence of authentication overhead.

# Repository Contents
- Source code for implementing the PPO-DRL model of authenticated offloading algorithms.

# Prerequisites
Python 3.11.3 and PyTorch 2.1.2

# Installation
Open a new terminal

Clone the repository:
- git clone https://github.com/sarahalshareeda/IBC-Task-Offloading-6G-VTN-PPO-DRL.git. Now you have a folder called "IBC-Task-Offloading-6G-VTN-PPO-DRL".

If any installation is needed for the imported libraries in the code, use:
- pip install the_lib_name

Running Simulations:
- Jupyter Notebook was used to write the code, so if you prefer to use it, go to https://jupyter.org/install to install Jupyter
- To run the simulations with default settings, then:
  1) change to the created directory: cd IBC-Task-Offloading-6G-VTN-PPO-DRL
  2) then type: jupyter lab

Once your browser window opens, click on the related "code" file. For latency and offloading percentage vs different network sizes, task sizes, and data rates, use the cloud-ibc-rate.ipynb

P.S. You can play and choose whatever hyperparameters, network size, task size, and data rates you want to experiment with.

# Author
Sarah Al-Shareeda (CAR-OSU USA, BTS-ITU Turkey, BCRG UK)
