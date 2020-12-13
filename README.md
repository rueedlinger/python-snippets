# Python Snippets

These __Python Snippets__ are tested with Python 3.6.x. All snippets are 
available as Jupyter notebooks (http://jupyter.org/).


## Getting Started
All the required Python packages can be installed with `pipenv`.

### Project Setup
First you nee to install `pipenv`.

```bash
$ pip install --user pipenv
```

Install all the required packages

```bash
$ pipenv install --dev
```

### Run the Notebook
You can start `jupyter-lab` to play around with the Juypter notebooks.


```bash
pipenv run jupyter-lab
```

### Run the Tests (nbval)
To test the Jupyter notebooks this project uses [nbval](https://github.com/computationalmodelling/nbval), which is a `py.test` 
plugin for validating Jupyter notebooks.


This will check all Jupyter notebooks for errors.

```bash
pipenv run py.test --nbval-lax
```

### Upgrade Python Packages
Check which packages have changed.

```
pipenv update --outdated
```

This will upgrade everything.

```bash
pipenv update
```

## CI Build (GitHub Actions)
- ![CI Build](https://github.com/rueedlinger/python-snippets/workflows/CI%20Build/badge.svg)

## The Python Snippets
The Python snippets are organized by topic.

__GeoJSON__
- [Convert a pandas DataFrame to GeoJSON (Stations) ](geojson/geojson_stations.ipynb)

__RSS__
- [Parse a RSS feed with feedparser](rss/feedparser.ipynb)

__HTTP__
- [Load the content from a website with urllib.request](http/urlib.ipynb)
- [Extract the text from a HTML document with Beautiful Soup](http/beautifulsoup4.ipynb)

__Image__
- [Image diff with scikit-image](image/image_diff.ipynb)