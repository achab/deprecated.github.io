---
layout: post
title:  "Some theory"
date:   2015-12-18 16:00:00
---

We first introduce the soft-max function:
```
f(x_1, ..., x_m) = \log (\sum_{i=1}^m) e^{x_i})
```

This function is differentiable and outputs ```\max_i x_i``` when one of the input is significantly bigger than the other.
