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

Git LFS isn't used for this repo as the datasets are small, and we are using the GitHub `https://raw.githubusercontent.com/` to get the data.
