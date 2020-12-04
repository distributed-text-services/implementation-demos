Demo for DTS Implementation uses
================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mromanello/implementation-demos/HEAD)

This repository contains a set of Jupyter notebooks that demonstrate how to query and interact with existing [DTS](https://w3id.org/dts) APIs.

## To come

🎁

## Alternative browsing demos

Alternatively, we provide two more point-and-click-y demos:

- [DTS demo](https://dev.chartes.psl.eu/dts-demo/) by the École Nationale des Chartes
- [DTS browser](https://dts-browser.herokuapp.com/) (⚠️ experimental!)

## How to run

1. Launch it on [Binder](https://mybinder.org) by cliking on the link above.

2. Or create a virtual environment to run the following notebooks before running the following commands. The notebooks run on 3.5 and later. It works on 3.8 (tested).

### Install

```bash
# Install the python libraries
pip install -r requirements.txt

# Install the jupyter extensions
jupyter contrib nbextension install --user
```

Then, run `jupyter notebook` and go to http://localhost:8888/nbextensions/?nbextension=zenmode/main where you enable `Table of Contents (2)`

### Run

To run, simply type in the terminal `jupyter notebook` and open one of them !
