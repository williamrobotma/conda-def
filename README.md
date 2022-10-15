# conda-def
Baseline environment for conda environment.

To create environment:
```
conda env create -f environment.yml
```

To use environment as template:
```
conda create -n ENV_NAME --clone def
```

To update environment:
```
conda update -n def --all
```