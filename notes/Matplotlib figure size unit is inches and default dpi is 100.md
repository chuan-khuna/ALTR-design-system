- **figure unit**, ie `figsize=(8, 6)`: inch
  - `figsize=(width, height)`
- **default dpi** `rcParams['figure.dpi']`: 100

> The native figure size unit in Matplotlib is inches, deriving from print industry standards. However, users may need to specify their figures in other units like centimeters or pixels

> Because of the default `rcParams['figure.dpi'] = 100`, one can mentally divide the needed pixel value by 100

https://matplotlib.org/stable/gallery/subplots_axes_and_figures/figure_size_units.html