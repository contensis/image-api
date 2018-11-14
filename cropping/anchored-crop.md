---
description: The anchored crop mode extracts a region of the original image to the exact dimensions specified from a specific location.
---

# Anchored crop

Extract a region of the original image with a given width and height. You can specify the [anchor](#anchor) parameter to select which part of the image to extract, or use exact [coordinate cropping](exact.md).

![](https://zenhub.zengenti.com/image-examples/tree-frog-anchor-example.jpg?width=1000&quality=50)

---

## Crop the original image to 1500x1500px from the center

!INCLUDE "../examples/crop-center.html"

---

## Crop the original image to 1500x1500px from the bottom left

!INCLUDE "../examples/crop-bl.html"

## Anchor


Position | Standard | Short
---------|-----------------
Top | top | t
Top right |  top-right | tr
Right | right | r
Bottom right | bottom-right | br
Bottom | bottom | b
Bottom left | bottom-left | bl
Left | left | l
Top left | top-left | tl
Center | center| c