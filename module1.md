# module 1

setup jupyter notebook and export it

## setup and config virtual env

``` py
python3 -m venv env
```

activate virtual environment

``` py
source env/bin/activate
```

deactivate

``` py
source deactivate
```

## install jupyter

note venv should be active

``` py
pip install --upgrade pip
```

``` py
pip install jupyter
```

``` py
python3 -m pip freeze > requirements.txt
```

## start jupyter notebook

``` py
jupyter notebook
```

## inside jupyter notebook

- create new notebook -> save as `getting-started-with-jupyter`
- create a hello_world function
- create markdown cell
