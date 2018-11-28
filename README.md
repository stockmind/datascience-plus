# Jupyter Data Science Notebook

This is a Docker image based on my Jupyter Sql Notebook, which in turn is based on the official Jupyter Data Science Notebook.
This image just adds some useful packages.

## Launch

```bash
    git clone https://github.com/stockmind/datascience-plus.git
    cd datascience-plus
    docker-compose up
```

## Remove

```bash
    cd datascience-plus
    docker-compose down
```

## Packages

```
- plotly        # Python framework for building analytics web apps
- ujson         # Ultra fast JSON encoder and decoder written in pure C with bindings for Python
- tinydb        # Tiny, document oriented database
- openpyxl      # Python library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files
- orca          # Pipeline orchestration framework
```