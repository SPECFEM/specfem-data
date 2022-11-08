# SPiRal model files for SPECFEM3D_GLOBE


These model files can be used for the SPECFEM3D_GLOBE repository and moved/linked to:
``
SPECFEM3D_GLOBE/DATA/spiral1.4
``


**file**: spiral1.4.tar.bz2

- compressed by `tar cvjf spiral1.4.tar.bz2 ./spiral1.4`

- decompress by `tar xvjf spiral1.4.tar.bz2` <br>
and move folder into SPECFEM3D_GLOBE/DATA/


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
git lfs pull --include "spiral1.4/<file>"
```

or if no git available:
```
wget https://github.com/SPECFEM/specfem-data/blob/main/spiral1.4/<file>?raw=true
```

You might have to uncompress the files you want using the bunzip2 command.
