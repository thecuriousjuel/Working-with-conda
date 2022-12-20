# Working with Conda environment

## 1.	Create a new environment
    > conda create -n python3.10 python=3.10

## 2.	Activate environment
    > conda activate python3.10

## 3. Install packages
    > pip install jupyterlab


## 4.	List all packages
    > pip list

## 5.	List all environments
    > conda env list

## 6.	Save package list to .txt file
    > pip list --format=freeze > requirements.txt

## 7.	Install packages from .txt file
    >  pip install -r requirements.txt


## 8.	Deactivate environment
    > conda deactivate

## 9.   Delete the environment
    > conda remove -n python3.10 --all

