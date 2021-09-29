# Data Ecosystems & Innovation Programme: Net Zero

## 1. Setup
The exploratory work is conducted in a Jupyter Notebook, which requires Python3 and jupyter Notebook to be installed. To install these and get set up follow these steps:

1. Install python3.9 [using pyenv](https://github.com/pyenv/pyenv)
2.  Create a local virtual environment for the repo and activate it, using
```
python3 -m venv venv
source venv/bin/activate
```
3. Install the necessary dependencies by running
```
python -m pip install -r requirements.txt
```
4. Start a jupyter notebook instance to access the exploratory work
```
jupyter notebook
```

## 2. Structure
The folder `data_sources` contains the data sources used in the exploratory work. At the moment there is only a ONS dataset, but this can be extended with other sources or different revisions of the `atmos_emis_ghg.xlsx` dataset to explore changes over time - useful for understanding any potential changes in methodologies.

The exploratory work is completed in the `UKNetZero.ipynb` file, which can be conveniently exported to a PDF file.