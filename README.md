# Feb-March 2021 vs Feb-March 2022 real estate market analysis.
Analysis of real estate market between February and March of 2021 and 2022.

# Requirements:
- MySQL server (https://dev.mysql.com/downloads/mysql/)
- mysql-connector-python (python -m pip install mysql-connector-python)
- pandas
- SqlAlchemy
- pymysql (needed to connect with MySQL server)

# Seting up virtual environment:
py -m venv .venv

.venv/Scripts/activate

python -m pip install --upgrade pip

## Install packages one by one:
python -m pip install pip-tools

python -m pip install ipykernel

python -m ipykernel install --user --name=.venv

## OR isntall packeges all at once from requirements.txt file:
python -m pip install -r /path/to/requirements.txt

## Remove virtual env from Jupyter Notebook:
jupyter kernelspec list

jupyter kernelspec uninstall .venv
