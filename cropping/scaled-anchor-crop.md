---
description: A scaled anchor crop allows the image to be cropped to exact dimensions from a set location, whilst cutting off some of the original image.
---
# Scaled crop

The scaled crop mode defines how the image should be scaled and aligned when the `fit=crop` parameter is set. The `width` and `height` parameters set both the crop dimensions and initial resize of the image. This crop mode ensures the image is always cropped to the exact dimensions specified, and results some of the original image being cut off.

Valid values for the crop position are `top`, `bottom`, `left`, `right`. If no value is explicitly set, the default behavior is to crop from the center of the image.


---

## Crop from center

!INCLUDE "../examples/scale-crop.html"

---

## Crop from top

!INCLUDE "../examples/scale-crop-top.html"

---

## Crop from right

!INCLUDE "../examples/scale-crop-right.html"

---

## Crop from bottom

!INCLUDE "../examples/scale-crop-bottom.html"

---

## Crop from left

!INCLUDE "../examples/scale-crop-left.html"