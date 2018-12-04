<!-- [![Build Status](https://travis-ci.org/atait/lytest.svg?branch=master)](https://travis-ci.org/atait/lytest) -->

# lymask

Mask dataprep with klayout.

Converts designer layouts to mask layouts that go to lithography machines.


## Installation
```
pip install lymask
```
The first time you do this, it will take about 10 minutes to build klayout.


## Usage
Invoke in the GUI menu or command line.

Dataprep processes are defined in YAML files. They can do.
- nanowire bulk sheath
- waveguide bulk sheath
- tiling
- cell flattening
- alignment marks, fiducials?

Todo: put tokens of these functions in here.