
https://matplotlib.org/stable/tutorials/text/text_props.html
> size or fontsize [ size in points | relative size, e.g., `'smaller'`, `'x-large'` ]

from [[Customising Matplotlib with rc Params|default matplotlib rcParams]]

```text
font.size:    10.0
lines.linewidth: 1.5               # line width in points

# The font.size property is the default font size for text, given in points. 10 pt is the standard value.

## Special text sizes can be defined
## relative to font.size, using the following values: xx-small, x-small,
## small, medium, large, x-large, xx-large, larger, or smaller
```


https://github.com/matplotlib/matplotlib/blob/v3.6.3/lib/matplotlib/font_manager.py#L896-L924

```python
font_scalings = {
  'xx-small': 0.579,
  'x-small': 0.694,
  'small': 0.833,
  'medium': 1.0,
  'large': 1.200,
  'x-large': 1.440,
  'xx-large': 1.728,
  
  'larger': 1.2,
  'smaller': 0.833,
  None: 1.0,
}
```