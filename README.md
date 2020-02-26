
# widget-jsmol

[![Build Status](https://travis-ci.org/osscar-org/widget-jsmol.svg?branch=master)](https://travis-ci.org/osscar-org/widget_jsmol)
[![codecov](https://codecov.io/gh/osscar-org/widget-jsmol/branch/master/graph/badge.svg)](https://codecov.io/gh/osscar-org/widget-jsmol)


A Jupyter widget to use Jmol/Jsmol.

## Installation

You can install using `pip`:

```bash
pip install widget_jsmol
```

Or if you use jupyterlab:

```bash
pip install widget_jsmol
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

If you are using Jupyter Notebook 5.2 or earlier, you may also need to enable
the nbextension:
```bash
jupyter nbextension enable --py [--sys-prefix|--user|--system] widget_jsmol
```
