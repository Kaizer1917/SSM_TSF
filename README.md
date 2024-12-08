# SSM_TSF

## Getting Started
### Environment
* python            3.10.13
* torch             1.12.1+cu116
* mamba-ssm         1.2.0.post1
* numpy             1.26.4
* transformers      4.38.2

The installation of mamba-ssm package can refer to https://github.com/state-spaces/mamba. 

### Run
To run SST on various dataset, run corrrsponidng dataset `.sh` files in the scripts folder. 

For exmaple, run SST on the Weather dataset: `./weather.sh`

### Dataset
You can download all the datasets from the "[Autoformer](https://drive.google.com/drive/folders/1ZOYpTUa82_jCcxIdTmyr0LXQfvaM9vIy)" project. Creatae a `dataset` folder in the current directory and put the downloaded datasets into `dataset` folder.
