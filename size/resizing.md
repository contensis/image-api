# Resizing

> Note: When using a width/height parameter greater than the original image width/height, the image is returned at it's original width/height value. If you are looking to upscale an image you'll need to use the [fit=contain](fit-contain.md) parameter.

## Width

Image width represents the width of the output image. The `width` or `w` parameter allows you to dynamically resize the image based on pixels values. If only the width is provided, then the image is scaled to the new dimension while retaining the original aspect ratio.

!INCLUDE "../examples/resize-width.html"

---

## Height

Image height represents the height of the output image. The `height` or `h` parameter allows you to dynamically resize the image based on pixels values. If only the height is provided, then the image is scaled to the new dimension while retaining the original aspect ratio.

!INCLUDE "../examples/resize-height.html"

---

## Width and height

When both the `width` and `height` parameters are provided, the image is resized so that it takes up as much space as possible within the bounding box defined by the given width and height parameters. The original aspect ratio is retained and all of the original image is visible.

!INCLUDE "../examples/resize-wh.html"
