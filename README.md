This repo is source code for cikm2024 paper "Learning to Discover Anomalous Trajectory with Open-World State Space Model"
## Original Datasets
	We conduct all experiments on two taxi trajectories datasets: Porto and Chengdu.
## Document description
	We have two folders:data and embedding.
	In the data folder, we have the partitioned data of the two datasets and the file process.py which preprocesses the data.In the embedding folder, 
	we have the embedding file which we have generated and the file which generates the embedding.
	Under current files there are files for model definition, model training etc.
## Usage
	To achieve ATRO task, run the ATRO_train.py. To achieve OATD task, run the OATD_train.py.
## Environments
	-python 3.8
	-pytorch 1.10
	-einops 0.7.0
	-torchmetrics 1.2.1
