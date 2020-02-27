
# widget-jsmol

A Jupyter widget to use Jmol/Jsmol.

## Installation

You can install using `pip`:

```bash
pip install widget_jsmol
```

Or if you use jupyterlab:

```bash
pip install widget_jsmol
jupyter labextension install @osscar/widget_jsmol
```

If you are using Jupyter Notebook 5.2 or earlier, you may also need to enable
the nbextension:
```bash
jupyter nbextension enable --py [--sys-prefix|--user|--system] widget_jsmol
```

## Usage

```python
from widget_jsmol import WidgetJmol

w = WidgetJmol()
display(w)
```
![Image of Jmol](/images/Jmol.png)

Load new file by using the structure element:

```python
w.structure = "/H2O/POSCAR"
```

Run the Jmol/Jsmol script:

```python
w.script = "set background red"
```

This widget need internet to fetch Jsmol files to show the visualizer.
