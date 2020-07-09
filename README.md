# pipeline-installers
This repository contains a collection of anaconda environment files used to install our analaysis pipelines. 

## Usage

### Install CaImAn pipeline
To install our [CaImAn](https://github.com/flatironinstitute/CaImAn) pipeline for miniscope analysis, do the following

```bash
# go to the pipeine-installers directory
$ cd <path to pipeline-installers folder>

# create create the environment and install the dependencies
$ conda env create -f caiman_pipeline.yaml

# verify the installation was complete
$ conda activate caiman
```