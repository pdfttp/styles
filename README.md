# styles
The billinge group matplotlib style sheet.

## Workflow
1. clone to local drive via `git clone https://github.com/pdfttp/styles.git`
1. put the following into your plot generating code:
```python
import os
import matplotlib.pyplot as plt
plt.style.use(os.path.join('/path/to/this/folder', 'billinge.mplstyle'))
```
where `'/path/to/this/folder'` is where the path points to the location of the repo on your local hard-drive 

####Or

If you are doing more intense work and are expecting to need to change this please:

1. copy `billinge.mplstyle` into the local directory of your work
1. use the above code with the filepath of the new directory. 

Please make a point of keeping the new (paper, poster, grant, etc.) specific style sheet in the version control of the larger work.

Please note that one can also change the specific style features (plot size, color map, etc.) inside the python code using the appropriate matplotlib code.