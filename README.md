
# Mapbox MBtiles Utilities

A Python 3.x (only!) library for working with [Mabox mbtiles v1.1](https://github.com/mapbox/mbtiles-spec/blob/master/1.1/spec.md)

[![Build Status](https://travis-ci.org/consbio/pymbtiles.svg?branch=master)](https://travis-ci.org/consbio/pymbtiles) [![Coverage Status](https://coveralls.io/repos/github/consbio/pymbtiles/badge.svg?branch=master)](https://coveralls.io/github/consbio/pymbtiles?branch=master)

Python 2.7.x is not supported at this time due to different sqlite3 API.


## Goals
* Provide a very lightweight API for reading / writing mbiles files



## Installation
For now, while this is under active development, install from master
branch on GitHub using pip:
```
pip install git+https://github.com/consbio/pymbtiles.git --upgrade
```

Once functionality stabilizes, it will be added to
[PyPi](https://pypi.python.org/pypi)


## Usage

### Python API
TODO:

*Note:*
* tiles are output to mbtiles format in xyz tile scheme.


### Metadata / descriptive attributes
TODO

## Credits:
Tile package format is described [here](https://gdbgeek.wordpress.com/2012/08/09/demystifying-the-esri-compact-cache/).

Inspired by:
* [mbutil](https://github.com/mapbox/mbutil)
* [node-mbtiles](https://github.com/mapbox/node-mbtiles)

SQL for creating mbtiles database derived from
[node-mbtiles](https://github.com/mapbox/node-mbtiles)


## License:
See LICENSE.md