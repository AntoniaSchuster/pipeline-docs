# QBiC Pipelines

This repository contains the documentation necessary to run different types of analysis in our clusters at QBIC.

## Contributing to the documentation

## Checking the documentation locally

To check locally how the documentation is building, you need to install the `sphinx`, `recommonmark` and `httpserver` dependencies. It requires Python 3!

```bash
pip install sphinx recommonmark httpserver
```

Then clone this repository from GitHub:

```bash
git clone git@github.com:qbic-pipelines/pipeline-docs.git
```

Go to the `/docs` directory of this repository and run:

```bash
make html
```

All the html files will be build under the `_build` directory. Then you can view the documentation in your browser by using the python built-in server:

```bash
python -m http.server
```

Navigate to the `_build` directory and you can check out locally the documentation.

## Setup the documentation

## Setup the server
