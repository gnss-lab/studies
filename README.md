# GNSS-LAB studies

# Prepare environment

We use anaconda to manage environments: to install particular python versions independent from system one and isolate projects dependencies from each other. You can use any similar tool to handle abive mentioned issues.

https://docs.conda.io/en/latest/

In anaconda propmt in windows or in linux terminal execute (change CASE_STUDY_NAME to appropriate study name):

```bash
conda deactivate
conda create -n CASE_STUDY_NAME python=3.10
conda activate CASE_STUDY_NAME
conda install jupyterlab
conda install cartopy
```

Clone the code with [git](https://git-scm.com/) or download [zip-archive](https://github.com/gnss-lab/studies/archive/refs/heads/main.zip) from repository [page](https://github.com/gnss-lab/studies).

```bash
git clone https://github.com/gnss-lab/studies.git gnss-lab-studies
cd gnss-lab-studies
```

And we are ready to go:

```
jupyter-lab
```

The notebook should work on other python version, however it is tested using python 3.10.

## Studies list

[Turkey earthquake February 6, 2023](./Turkey_EQ_2023/README.md)

[Starship November 18, 2023](./Starship_2023/README.md)
