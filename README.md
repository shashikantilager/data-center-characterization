# Analysis of Data Center Logs
This repository contains code for the a statistical analysis of a cloud data center logs (described in this [paper](http://hpc.ec.tuwien.ac.at/files/UCC_23_data_center_analysis.pdf)). This project uses jupyter notebook for statistical analysis and also for plotting. 

## Data Access

Please download the  the data from [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10069402.svg)](https://zenodo.org/doi/10.5281/zenodo.10069401)
 and store the downloaded files   in directory `/data/datasets/combined/`
 

# Running the  notebook

You can  run either on local juyter server or on your preferred IDE (e.g., VS Code)  with your own virtual environment and notebook plugins. 

## Requirements
```shell
python3 -m venv venv
source venv/bin/activate

pip install notebook

jupyter notebook

pip install -r requirements.txt
```


## Citation Information
Shashikant Ilager, Adel N. Toosi, Mayank Raj Jha, Ivona Brandic, Rajkumar Buyya, "A Data-driven Analysis of a Cloud Data Center: Statistical Characterization of Workload, Energy and Temperature", In Proceedings of the 16th IEEE/ACM International Conference on Utility and Cloud Computing (UCC2023), Vancouver, Messina, Italy, December 4-7, 2022. [[pdf]](http://hpc.ec.tuwien.ac.at/files/UCC_23_data_center_analysis.pdf)