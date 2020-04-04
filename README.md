# Introduction to Machine Learning (Udacity Course)
Notes, exercises, examples etc

# Setup and commands
## Conda environments
### Create env
```
conda create --name default37 python=3.7

#
# To activate this environment, use
#
#     $ conda activate default37
#
# To deactivate an active environment, use
#
#     $ conda deactivate

```
### List envs
```
conda env list
```
### Remove an environment
```
conda remove --name ak-default --all
```

## Handling packages in an environment
```
# Activate env to install into
conda activate default37

# List packages already installed in env
conda list

# Install a new package
conda install <package_name>
```

## Install required packages
```
conda install python=3.7
conda install jupyter notebook
conda install nb_conda
```

# References
* [Conda - User Guide](https://docs.conda.io/projects/conda/en/latest/user-guide/index.html)