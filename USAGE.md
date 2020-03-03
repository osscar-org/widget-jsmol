# Usage

## import the widget for widget_jsmol 

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

<span style="color:red"> *This widget need internet to fetch Jsmol files to show
the visualizer.*</span>
