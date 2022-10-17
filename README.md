# conda-def
Baseline environment for conda environment.

To create environment:
```
conda env create -f environment.yml
```

To update environment:
```
conda update -n def --all
```

To use environment as template:
```
conda create -n ENV_NAME --clone def
```

Alternatively, one can use the environment file itself as a template. This could 
be beneficial as one does not need to create and maintain the def environment, 
however it will take longer to resolve and possibly download / install packages.

To do this, simply use the -n flag to specify environment name:
```
conda env create -n ENV_NAME -f environment.yml
```
