---
title: initialize_2d_list
tags: list,intermediate
---

Initializes a 2D list of given width and height and value.

Use list comprehension and `range()` to generate `h` rows where each is a list with length `h`, initialized with `val`.
If `val` is not provided, default to `None`.

Explain briefly how the snippet works.

```py
def initialize_2d_list(w,h, val = None):
  return [[val for x in range(w)] for y in range(h)]
```

```py
initialize_2d_list(2, 2, 0) # [[0,0], [0,0]]
```
