# MCSNET

Maximum Common Subgraph Guided Graph Retrieval: Late and Early Interaction Networks

This directory contains code necessary for running all the experiments.

#Requirements

Recent versions of Pytorch,Pytorch Geometric, numpy, scipy, sklearn, networkx and matplotlib are required.  
You can install all the required packages using  the following command:

	$ conda create --name <env> --file requirements.txt

#Datasets
Please download the Datasets files from https://rebrand.ly/mcsnet and replace the current dummy Datasets folder.
This contains the original datasets, the dataset splits and other intermediate data dumps for reproducing tables and plots.  


#Run Eperiments

The command lines to used for training models are listed commands.txt.   
Command lines specify the exact hyperparameter settings used to train the models.   

#Reproduce plots and figures  

The notebooks folder contains .ipynb files which reproduce all the tables and figures presented in the paper.   

Notes:  
 - GPU usage is required  
 - source code files are all in mcs folder.

Reference
---------

If you find the code useful, please cite our paper:

	@article{roy2022maximum,
	  title={Maximum common subgraph guided graph retrieval: late and early interaction networks},
	  author={Roy, Indradyumna and Chakrabarti, Soumen and De, Abir},
	  journal={Advances in Neural Information Processing Systems},
	  volume={35},
	  pages={32112--32126},
	  year={2022}
	}

Indradyumna Roy, Indian Institute of Technology - Bombay  
indraroy15@cse.iitb.ac.in

