---
aliases:
---

related to: [[Typography unit - Point (pt)|pt]] and [[Dot per Inch DPI|DPI]]

```python
def point_to_inch(pt, point_per_inch=72):
  return np.round(pt * (1 / point_per_inch), 2)
  

def inch_to_point(inch, point_per_inch=72):
  return np.round(inch / (1 / point_per_inch), 1)
  

def inch_to_pixel(inch, dot_per_inch=300):
  return np.round(inch * dot_per_inch, 1)


def pixel_to_inch(pixel, dot_per_inch=300):
  return np.round(pixel * (1 / dot_per_inch), 2)
```