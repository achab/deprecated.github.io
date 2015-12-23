<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

---
layout: post
title:  "Some theory"
date:   2015-12-18 16:00:00
---
## Soft-max function
We first introduce the soft-max function:
```
f(x_1, ..., x_m) = log [ sum_{i=1}^m) exp( x_i) ]
```

This function is differentiable and outputs ```max_i x_i``` when one of the input is significantly bigger than the other.

## Outer product
*Definition (abstract)*:

Let V and W be vector spaces. W^* is the dual space of W. Given ```x``` in V, and ```y^*``` in W^*, the outer (or tensor) product y^* \otimes x corresponds to the map A from W to V such that

A(w) = y^* (w) x

The interpretation is easy when V and W take the form \mathbb{R}^dim.

## SVM dual optimization problem
\sum_i a_i - 1/2 \sum_{ij} a_i a_j subject to qqch
