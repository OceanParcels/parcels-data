# Parcels Data

## Overview

This repository contains datasets for use in [Parcels](https://github.com/OceanParcels/parcels) tutorials or examples.

## Available datasets

See [parcels/tools/exampledata_utils.py](https://github.com/OceanParcels/parcels/blob/main/parcels/tools/exampledata_utils.py) for a list of available datasets.


## Adding a new dataset

1. Choose a (filename safe) name for your dataset. This will be used as a key to refer to the dataset in the Parcels, and will also be the name of the folder.
2. Assuming you have your folder with your data files. E.g., 

```
MovingEddies_data
├── moving_eddiesP.nc
├── moving_eddiesU.nc
└── moving_eddiesV.nc
```
just move this to the `data` directory.

3. Update [parcels/tools/exampledata_utils.py](https://github.com/OceanParcels/parcels/blob/main/parcels/tools/exampledata_utils.py) accordingly to include your new dataset.

All NetCDF files are tracked by Git LFS. If you want to expand the files included in Git LFS, see the [GitHub docs](https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage).
