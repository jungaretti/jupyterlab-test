# Codespaces in JupyterLab

1. `gh cs create -r jungaretti/jupyterlab-test -b friday-demo`
2. `gh cs jupyter` and select your new codespace
3. Execute some cells
4. Create a new notebook
5. Add some cells to a new notebook and execute them
6. Commit your changes and push them

## Example Cells

```python
import math
import matplotlib.pyplot as plt
```

```python
x=[1,2,3,4,5,6,7,8]
y=list(map(lambda x: math.pow(2, x), x))
plt.plot(x,y)
plt.show()
```
