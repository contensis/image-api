---
description: This article outlines how you can combine different query string parameters to apply multiple transformations.
---

# Multiple transformations

Transformations can be combined together to apply multiple changes to an image as part of a single delivery request, e.g. crop an image and then apply a grayscale image effect. In certain cases you may want to perform additional transformations on the result of another transformation request. In order to do that, you can chain the transformations together using an `&` ampersand character.

## Width

!INCLUDE "../examples/mt-w.html"

---

## Width and quality

!INCLUDE "../examples/mt-w-q.html"

---

## Width, quality and grayscale effect

!INCLUDE "../examples/mt-w-q-e.html"