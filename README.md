# E8Lattice


## Features

- Startup name generator

## Background

- What is iPython?

- Why do we need Jupyter notebooks?


## Steps

* Setup virtual environment
```
python3 -m venv venv

source venv/bin/activate


```

* Install Miniforge
```
brew install miniforge
```

* Run conda init bash / zsh
```
==> conda init bash
no change     /opt/homebrew/Caskroom/miniforge/base/condabin/conda
no change     /opt/homebrew/Caskroom/miniforge/base/bin/conda
no change     /opt/homebrew/Caskroom/miniforge/base/bin/conda-env
no change     /opt/homebrew/Caskroom/miniforge/base/bin/activate
no change     /opt/homebrew/Caskroom/miniforge/base/bin/deactivate
no change     /opt/homebrew/Caskroom/miniforge/base/etc/profile.d/conda.sh
no change     /opt/homebrew/Caskroom/miniforge/base/etc/fish/conf.d/conda.fish
no change     /opt/homebrew/Caskroom/miniforge/base/shell/condabin/Conda.psm1
no change     /opt/homebrew/Caskroom/miniforge/base/shell/condabin/conda-hook.ps1
no change     /opt/homebrew/Caskroom/miniforge/base/lib/python3.10/site-packages/xontrib/conda.xsh
no change     /opt/homebrew/Caskroom/miniforge/base/etc/profile.d/conda.csh
modified      /Users/coder/.bash_profile
```

Open a new terminal to load the .bash_profile environment variables into your shell. Then, create a conda environment using the following command
conda create --name e8lattice python=3.8 pip
This should give us the below prompt 
==> conda create --name e8lattice python=3.8 pip
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /opt/homebrew/Caskroom/miniforge/base/envs/e8lattice

  added / updated specs:
    - pip
    - python=3.8

The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    python-3.8.15              |h3ba56d0_1_cpython        11.2 MB  conda-forge
    setuptools-66.1.1          |     pyhd8ed1ab_0         630 KB  conda-forge
    ------------------------------------------------------------
                                           Total:        11.8 MB

The following NEW packages will be INSTALLED:

  bzip2              conda-forge/osx-arm64::bzip2-1.0.8-h3422bc3_4
  ca-certificates    conda-forge/osx-arm64::ca-certificates-2022.12.7-h4653dfc_0
  libffi             conda-forge/osx-arm64::libffi-3.4.2-h3422bc3_5
  libsqlite          conda-forge/osx-arm64::libsqlite-3.40.0-h76d750c_0
  libzlib            conda-forge/osx-arm64::libzlib-1.2.13-h03a7124_4
  ncurses            conda-forge/osx-arm64::ncurses-6.3-h07bb92c_1
  openssl            conda-forge/osx-arm64::openssl-3.0.7-h03a7124_2
  pip                conda-forge/noarch::pip-22.3.1-pyhd8ed1ab_0
  python             conda-forge/osx-arm64::python-3.8.15-h3ba56d0_1_cpython
  readline           conda-forge/osx-arm64::readline-8.1.2-h46ed386_0
  setuptools         conda-forge/noarch::setuptools-66.1.1-pyhd8ed1ab_0
  tk                 conda-forge/osx-arm64::tk-8.6.12-he1e0b03_0
  wheel              conda-forge/noarch::wheel-0.38.4-pyhd8ed1ab_0
  xz                 conda-forge/osx-arm64::xz-5.2.6-h57fd34a_0

Proceed ([y]/n)?
After the packages have downloaded and extracted, one may activate the conda environment as below
conda activate e8lattice
One may also export the yml file of the conda environment with the below command
conda env export > environment.yml

* Deactivate conda virtual env
```
conda deactivate
```
