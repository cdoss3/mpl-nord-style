# mpl-nord-style
Nord styling for Matplotlib figures.

The file uses the default Matplotlib .mplstyle file, with changes uncommented.

To use, download the .mplstyle file, and link to it in your script:

...
from matplotlib import pyplot as plt
...
plt.style.use('{path_to_file}/nord.mplstyle')
