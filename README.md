# Python Snippets

These __Python Snippets__ are tested with Python 3.6.x. All snippets are 
available as Jupyter notebooks (http://jupyter.org/).


## Get started...
To get started create a virtual environment and install the required packages. 

- Juypter Notebook
- pandas 
- geojson
- beautifulsoup4
- feedparser
- scikit-image 
- matplotlib


### Conda
The following example shows how to create an environment with _"conda"_ 
(http://conda.pydata.org/) and Python 3.6 with
the required packages.

```bash
conda create -n py36-ps python=3.6

source activate py36-ps

``` 

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