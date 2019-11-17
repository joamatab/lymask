<!-- [![Build Status](https://travis-ci.org/atait/lytest.svg?branch=master)](https://travis-ci.org/atait/lytest) -->

# lymask

Mask dataprep with klayout.

Converts designer layouts to mask layouts that go to the lithography machines.


## Installation
```
pip install lymask
```
The first time you do this, it will take about 10 minutes to build klayout. We assume that you have this, AND that the Technology bug has been fixed.


## Usage
Invoke in the GUI menu or command line.

Dataprep processes are defined in YAML files in the "dataprep" directory. They can do.
- nanowire bulk sheath
- waveguide bulk sheath
- tiling
- cell flattening
- alignment marks, fiducials?

Todo: put tokens of these functions in here.

## Running tests
To test command line and API, run `pytest tests`

You can also go in the GUI and do it there, but that has to be manual

This is also CI tested by Travis

## DRC todo
XX - batch launching
XX - output to lyrdb files
XX - command line reorganization
XX - tests: generate the files and compare as xmldicts
XX - angle limits
- tiling
- drc exclude
- falling back on designer layers?
XX - inclusion, exclusion
- self overlap
- minimum area
- edge lengths
