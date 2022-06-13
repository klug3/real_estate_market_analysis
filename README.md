# otodom_intern_assignment
Job assignment for intern Data Analyst position at Otodom (OLX Group).

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

python -m pip install pip-tools

python -m pip install ipykernel

python -m ipykernel install --user --name=.venv

## Remove virtual env from Jupyter Notebook:
jupyter kernelspec list

jupyter kernelspec uninstall .venv
