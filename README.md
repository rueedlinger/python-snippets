# Python Snippets

These __Python Snippets__ are tested with Python 3.5.x. (http://conda.pydata.org/)

## Get started...
To get started create a virtual environment and install the required packages. 
The following example shows how to crate an environment with _conda_ and Python 3.5 with
the required packages.

```bash
conda create -n py35-ps python=3.5 -f requirements.txt

source activate py35-ps

pip install -r requirements.txt
``` 

## The snippets...

__GeoJSON__
- [GeoJSON Example - Stations](geojson/geojson_stations.ipynb)
