---
description: The Image API supports the rotation of images. This article outlines how you can change the orientation of your images. 
---

# Rotation

The `rotate` or `r` parameter allows you to rotate an image by any arbitrary angle in degrees. The value is an integer between 0 and 359, rotating the image clockwise. If the angle is not a multiple of 90 then a rectangular bounding box is added containing the rotated image and empty space, the background color can be specified by the `background` or `bg` parameter hex value.

---

## Rotate by 90 degrees

!INCLUDE "../examples/rotate-90.html"

---

## Rotate by 180 degrees

!INCLUDE "../examples/rotate-180.html"

---

## Rotate by 340 degrees

!INCLUDE "../examples/rotate-340.html"



