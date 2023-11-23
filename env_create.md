# Creating the conda env
    conda create --name vename python=3.9
    conda activate vename


## Creating venv kernel
    conda install ipykernel
    conda install nb_conda_kernels

## Adding venv to conda kernels
    python -m ipykernel install --user --name vename

### Deleting venv
    jupyter kernelspec uninstall vename


# making powershell work

    conda init powershell # inside the administrator powerhsell
    
