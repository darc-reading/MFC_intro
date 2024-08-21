# Ensemble Kalman filter tutorial

This repository is a practical of ensemble Kalman filter that is derived from DARC training course material for data assimilation. The practical is in the Jupyter notebook [Controls_L96_Enkf_MFC.ipynb](Controls_L96_Enkf_MFC.ipynb).


## Running the Jupyter notebok
There are three ways to run the jupyter notebook:
### Using binder
  Open the link for binder: https://mybinder.org/v2/gh/darc-reading/MFC_intro/HEAD
### Using Google Colab
- From [Google Colab](https://colab.research.google.com/github/darc-reading/DA-training-2024/):
  - Adding these two lines at the start of the notebook
    ```ipython
       !git clone https://github.com/darc-reading/MFC_intro.git
       %cd MFC_intro
    ```
### On local laptop (Python version >= 3.8):
  - obtain the code:
    - directly download the code as zip
    - using git: `git clone https://github.com/darc-reading/MFC_intro.git`
  - change your working directory to `MFC_intro`
  - create a virtual environment in your Python in your terminal:
    `python -m venv mfc_enkf`
  - activate the virtual environment:
    - Linux/Mac `source mfc_enkf/bin/activate`
    - Windows command prompt: `mfc_enkf/Scripts/activate.bat` 
    - Windows powershell: `mfc_enkf/Scripts/Activate.ps1`
  - install dependencies: `pip install -r requirements.txt`
  - open jupyter notebook: `jupyter notebook`
