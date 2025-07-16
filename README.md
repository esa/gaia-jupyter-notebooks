[//]: # (Copyright &#40;c&#41; European Space Agency, 2025.)
[//]: # ()
[//]: # (This file is subject to the terms and conditions defined in file 'LICENCE.txt', which)
[//]: # (is part of this source code package. No part of the package, including)
[//]: # (this file, may be copied, modified, propagated, or distributed except according to)
[//]: # (the terms contained in the file ‘LICENCE.txt’.)
[![License: ESA permissive](https://img.shields.io/badge/ESA%20Public%20License-Permissive-blue.svg)](https://github.com/esa/gaia-jupyter-notebooks/blob/main/LICENSE.txt)

# Gaia ESA Archive Tutorials

## Description
This repository contains a set of programmatic tutorials in the form of jupyter notebooks that show how to access, retrieve, and explore different datasets served by the Gaia ESA Archive.

## Usage
Each notebook in this repository is self-contained and includes detailed instructions and examples. 


## Installation

### Prerequisites
- Miniconda or Anaconda installed
- Python 3.x

### Setup
To create the conda environment, run the following command:
```bash
CONDA_SUBDIR=osx-64 conda env create -f data-release-3-tutorials/environment.yml
```

To activate the environment:
```bash
conda activate gaia_archive_tutorial
```

## License
This project is licensed under the terms included in the [LICENSE.txt](LICENSE.txt) file.

### Third-Party Dependencies
To generate the list of third-party dependencies and their licenses, run:
```bash
pip install pip-licenses
pip-licenses --format=markdown --output-file=third-party-licenses.md
```

## Contact

In case of questions or issues, please open an issue in the repository or contact the maintainers through the Gaia Helpdesk at [gaia-helpdesk@esa.int](mailto:gaia-helpdesk@esa.int).
