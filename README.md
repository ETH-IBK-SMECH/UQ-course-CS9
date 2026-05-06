# UQ-course-CS9

This repository contains the code of the tutorial for the block CS9 of the course "UQ & Data Analysis in Applied Sciences".

The code is tested on Linux. If your OS is Windows, it is strongly suggested to install WSL2 (https://learn.microsoft.com/en-us/windows/wsl/install) and a Linux distr (e.g., Ubuntu 20.04).

## Setup

Clone repository:
```bash
git clone https://github.com/ETH-IBK-SMECH/UQ-course-CS9.git
cd UQ-course-CS9
```

Make sure a C++ compiler is installed (PyMC uses it to compile sampling code).
On Ubuntu/Debian:
```bash
sudo apt update && sudo apt install -y build-essential
```

Create the conda environment:
```bash
conda create -n cs9 python=3.8 mkl mkl-service -c conda-forge
conda activate cs9
```
Install requirements:
```bash
pip install -r requirements.txt
```
