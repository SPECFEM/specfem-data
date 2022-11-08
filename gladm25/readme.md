# GLAD-M25 model files for SPECFEM3D_GLOBE


These model files can be used for the SPECFEM3D_GLOBE repository and moved/linked to:
``
SPECFEM3D_GLOBE/DATA/gladm25
``


**file**: gladm25.tar.bz2

- compressed by `tar cvjf gladm25.tar.bz2 ./gladm25`

- decompress by `tar xvjf gladm25.tar.bz2` <br>
and move folder into SPECFEM3D_GLOBE/DATA/


This folder is a barebone version only with the needed model files (in `crust/` and `mantle/` folders) 
from repository [gladm25](https://github.com/caiociardelli/gladm25)


### Git LFS

Files are stored by [Github LFS](https://git-lfs.github.com). To retrieve the all data, either clone the repository:
```
$ git clone https://github.com/SPECFEM/specfem-data.git
```
or if already done use the git command to update your local files:
```
$ git pull
```


To download a single file:
```
git lfs pull --include "gladm25/<file>"
```

or if no git available:
```
wget https://github.com/SPECFEM/specfem-data/blob/main/gladm25/<file>?raw=true
```

You might have to uncompress the files you want using the bunzip2 command.
