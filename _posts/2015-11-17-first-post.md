---
layout: post
title:  "First post: examples of content styles"
date:   2015-11-17 13:32:15
---

## Quote

> This quote will change your life. It will reveal the secrets of the universe, and all the wonders of humanity. Don't misuse it.

## Code

Here is some html:

```html
<html>
  <head>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
```

Here is some python:

{% highlight python %}
from numpy.random import gumbel
def gumbel_max_sample(x):
    z = gumbel(loc=0, scale=1, size=x.shape)
    return (x + g).argmax(axis=1)
{% endhighlight %}
