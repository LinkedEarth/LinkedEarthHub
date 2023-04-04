[![PyPI version](https://badge.fury.io/py/pyleoclim.svg)](https://badge.fury.io/py/pyleoclim)
[![NSF-2126510](https://img.shields.io/badge/NSF-2126510-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=2126510)

# LinkedEarthHub
This repository contains information pertaining to the LinkedEarth Jupyter Hub. To learn more about the hub and how you can join, please see [this page](http://linked.earth/research_hub.html). 

## What is available on the hub?

### Environment

The Hub runs under Python 3.10 and contains the packages listed [here](https://github.com/LinkedEarth/LinkedEarthHub/blob/main/environment.yml) which should get you started with [Pyleoclim](https://pyleoclim-util.readthedocs.io/en/master/) and contains necessary libraries for model-data comparison (e.g., [xarray](https://docs.xarray.dev/en/stable/) and its ecosystem, including the handling of data in [zarr](https://zarr.readthedocs.io/en/stable/) format and libraries to query datasets stored in this format directly from your cloud environment). The goal is to work in this environment located close to the data. 

### Notebooks

To get you started, go to the shared folder: 

![Screenshot 2023-04-04 at 10 34 59 AM](https://user-images.githubusercontent.com/11758571/229872547-511b26fe-dea8-4d57-a620-a56ff6435c07.png)

* The `PaleoBooks` folder contains examples on how to use Pyleoclim and load data from model outputs. This works is still in progress and notebooks will be updated soon
* The `pyleoclim_paper` folder contains the three notebook exemplars that were published in [Paleoceanography and Paleoclimatology](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022PA004509). The notebooks can also be found [here](https://github.com/LinkedEarth/PyleoclimPaper). Note that these notebooks were written under `v0.9.` of Pyleoclim and will not be updated to the latest codebase. 
* The `pyleoclim_tutorials` folder contains short introductory tutorials on Pyleoclim. A JupyterBook version can be found [here](http://linked.earth/PyleoTutorials/intro.html). These tutorials will update to the version of Pyleoclim used by the Hub. 

**Note**: This folder is in read-only. You can run the code but not modify the notebooks. If you want to work with one of them as a starting point, please move the notebook to your directory. 
