# Topography/bathymetry data files for SPECFEM3D_GLOBE


The binary files were created using the script from the SPECFEM3D_GLOBE repository:
``
SPECFEM3D_GLOBE/DATA/topo_bathy/run_create_topo_bathy_file.py
``

Files are stored by [Github LFS](https://git-lfs.github.com). To retrieve the topo data, either clone the repository:
```
$ git clone https://github.com/SPECFEM/specfem-data.git
```
or if already done use the git command to update your local files:
```
$ git pull
```


To download a single file:
```
git lfs pull --include "topo_bathy/<file>"
```

or if no git available:
```
wget https://github.com/SPECFEM/specfem-data/blob/main/topo_bathy/<file>?raw=true
```

You might have to rename the file and/or can now uncompress the topography file you want using the bunzip2 command.
You will also need to uncomment it in file setup/constants.h.in before configuring and compiling the SPECFEM3D_GLOBE code.
