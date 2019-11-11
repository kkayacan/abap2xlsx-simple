# abap2xlsx-simple
MS Excel interface library for SAP ABAP

This is a local-class & single-include version of [abap2xlsx](https://github.com/sapmentors/abap2xlsx) by [sapmentors](https://github.com/sapmentors). Created for easier installation and backwards compatibility. Based on [this commit](https://github.com/sapmentors/abap2xlsx/commit/36ea883d33cf337b9bbcc89ce3839fa03c0c44a2) of abap2xlsx . Many thanks to original contributers.

Tested on an ABAP 7.01 SP 13 system through demo programs 1-6 of original abap2xlsx repo.

## Installation
Either clone this repo with [abapGit](https://github.com/larshp/abapGit) or upload [this code](src/zabap2xlsx_simple.prog.abap) to a new include.

## Usage
Include the library in your program like this:
```
INCLUDE zabap2xlsx_simple.
```
Then refer to the [original documentation](https://sapmentors.github.io/abap2xlsx/) of abap2xlsx.

## Shortcomings
Huge file writer will not work due to requirement of simple transformations. Currently tested with only first 6 demo programs of original repo.