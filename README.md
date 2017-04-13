# TensorFlow

## Install Miniconda
[Download Link](https://conda.io/miniconda.html)

#### Mac OSX
```
$ bash Miniconda3-latest-MacOSX-x86_64.sh
```
If you use ZSH then 
run ```$ echo "export PATH=/Users/$USERNAME/miniconda3/bin:$PATH" >> ~/.zshrc```

## Install  Jupyter Notebook

```
$ conda install jupyter notebook
```

## (Optional) Install nb_conda_kernels

```
$ conda install -c conda-forge nb_conda_kernels
```
Here you can manage your environments from within Jupyter

## Create Environments
```
$ conda create -n tfpratice python=3.6
$ source activate tfpratice
$ conda install numpy pandas jupyter notebook matplotlib
```

## Run Jupyter Notebook
```
$ source deactive
$ jupyter notebook
```
press "New" button and select "tfpratice" kernal 

Start Coding!



