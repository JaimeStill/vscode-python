## Create a Virtual Environment

```py
py -3 -m venv .venv
.venv\scripts\activate
```

## Install Packages

```py
py -m pip install {package}

# example
py -m pip install pylint
```

## Generate .pylintrc

```py
pylint --generate-rcfile > .pylintrc
```

## Freeze Packages

```py
pip freeze > requirements.txt

# install from requirements.txt
pip install -r requirements.txt
```