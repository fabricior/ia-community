# ia-community

## MNIST example

### Working with a virtual Environment

While the environment is active, any package you install using pip will be installed in this isolated environment

#### Create Virtual Environment

`python -m pip install --user -U virtualenv`

`cd <repo-root>\mnist`

`python -m virtualenv mnist-env`

#### Activate Virtual Envinment (on Windows)

`cd <repo-root>\mnist`

`.\mnist-env\Scripts\activate.bat`

#### Deactivate Virtual Envinment (on Windows)

`cd <repo-root>\mnist`

`.\mnist\mnist-env\Scripts\deactivate.bat`

### Install Required packages

`python -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn`
