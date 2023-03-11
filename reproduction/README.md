# Reproduction of the project

Before starting, make sure that gcc is installed
```shell
sudo apt-get install gcc
```

Creating conda env and installing pytorch & cuda
```shell
conda create --name kinyabert python=3.8 pytorch cudatoolkit=11.0 -c pytorch
conda activate kinyabert
```

Now installing the requirements 
```shell
pip install -r ./reproduction/requirements.txt
```

but there's an optional library we need to install for mixed precision optimization

```shell
conda install -c conda-forge nvidia-apex
```
