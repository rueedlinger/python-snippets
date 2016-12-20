# Python Snippets

These __Python Snippets__ are tested with Python 3.5.x. All snippets are 
available as Jupyter notebooks (http://jupyter.org/).


## Get started...
To get started create a virtual environment and install the required packages. 

### Virtualenv
The following example shows how to create an environment with 
_"virtualenv"_ (https://virtualenv.pypa.io/)
and Python 3.5 with the required packages.

```bash
virtualenv --python=/usr/bin/python3.5 py35-ps

source py35-ps/bin/activate

pip install -r requirements.txt
``` 

### Conda
The following example shows how to create an environment with _"conda"_ 
(http://conda.pydata.org/) and Python 3.5 with
the required packages.

```bash
conda create -n py35-ps python=3.5

source activate py35-ps

pip install -r requirements.txt
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
- tbd