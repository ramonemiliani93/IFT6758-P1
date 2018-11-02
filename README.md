p1
==============================

Project 1 for IFT6758 (Data Science).

Project Organization
------------

+ LICENSE
+ README.md          <- The top-level README for developers using this project.
+ **data/** : generated by `src/data/download_dataset.py`
    + **processed/**: preprocessed mnist data
    + **raw/**: raw mnist data
+ **report/**: fact bombs for dr. tapp
+ `requirements.txt`: see `environment.yml` for conda environment
+ `setup.py`: i don't think we need this.
+ `setup.sh`: create conda environment.
+ `source.me`: a totally non-general way for jdv to load conda environments on his workstation.
+ **src/**
    + **data/**: data download + preprocessing script
    + **features/**: runs trained lenet on inputs to get distance values
    + **models/**: lenet
+ `run_experiments.py` : load data, load trained model, compute distances, classify, for all models.

