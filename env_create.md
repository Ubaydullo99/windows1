## 1. Creating the conda env
    conda create --name vename python=3.9
    conda activate vename


### Creating venv kernel
    conda install ipykernel
    conda install nb_conda_kernels

### Adding venv to conda kernels
    python -m ipykernel install --user --name vename

### Deleting venv
    jupyter kernelspec uninstall vename


### making powershell work

    conda init powershell # inside the administrator powerhsell
    




## 2. Creating a Virtual Environment with Python 3.7:
First, ensure you have Python 3.7 installed on your system.

For Windows:
Create a virtual environment named 'yolo' with Python 3.7:

    python3.7 -m venv yolo
    
Activate the virtual environment:

    .\yolo\Scripts\activate

After Activation:
Once activated, your command prompt will show the virtual environment name in the prefix (e.g., (yolo) C:\your\path>). You can install packages and run Python scripts within this isolated environment.

To deactivate the virtual environment and return to the global environment:

    deactivate

Please replace python3.7 with the appropriate command if your Python 3.7 interpreter is named differently on your system (e.g., python3.7, python3, etc.).



    D:\Programs\Python37-32\python.exe -m venv yolo77
