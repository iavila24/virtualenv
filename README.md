# Virtualenv
Practica de entornos virtuales con VENV, opciones (PIPENV) (POETRY)

### Steps to create a virutal environment on Python

1. Create repository on GITHUB
2. Clone reposotory
3. Execute the following command:
```bash
python -m venv env
```
4. Activate virtual environment
```bash
source env/Script/activate
```
4.1 Deactivate virtual enviroment
```bash
deactivate
```
5. Install ipython library
```bash
pip install ipython
```
6. Execute ipython
```bash
ipython
```
7. Show project dependencies
```bash
pip freeze
```
8. Share dependencies
```bash
pip freeze > requirements.txt
```
9. Install dependencies from file
```bash
pip install -r requirements.txt
```

`Exercise`: Escribir el texto "El profe rifa, lo quiero mucho ♥" con:
    1. asc
    2. colorama