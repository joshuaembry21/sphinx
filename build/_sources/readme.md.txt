# North By Northwest - Initial Production Prediction Model

---
# Requirements

## Production

---
### Required
* [Docker](https://www.docker.com/products/docker-desktop)
* Sync connection to the data shared [Google Drive](https://drive.google.com/drive/u/0/folders/1sjIsyMGj3R6v8Bzc1jY6IlP-pmlCv4cI)
* This repository
    * `git clone https://github.com/North-by-Northwest/Initial_Production_Prediction_Model`
    
### Suggested for Windows
* [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install-win10) with [Docker configured for windows use](https://docs.docker.com/docker-for-windows/wsl/)

---
## Local Development

---
General Requirements:
* Repository 
  * `git clone https://github.com/North-by-Northwest/Initial_Production_Prediction_Model`

* Data from [Google Drive](https://drive.google.com/drive/u/0/folders/1sjIsyMGj3R6v8Bzc1jY6IlP-pmlCv4cI)

For sandboxing ideas, a [docker jupyterlab instance](docker/pip/readme.md) is suggested

For debugging or script work:
* Create an appropriate [conda](https://www.anaconda.com/products/individual) [environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
```
conda create --name ippf python=3.8
conda activate ippf
pip install --upgrade dask distributed fitter fsspec geopy jupyter jupyterlab matplotlib numpy openpyxl pandas python-dateutil pyYAML pyarrow scikit-learn scipy tqdm xgboost xlrd
```

---
# Usage

---
see [docker/pip/readme.md](docker/pip/readme.md)

