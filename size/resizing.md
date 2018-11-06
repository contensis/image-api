# Resizing

## Width

Image width represents the width of the output image. The `width` or `w` parameter allows you to dynamically resize the image based on pixels values. If only the width is provided, then the image is scaled to the new dimension while retaining the original aspect ratio.

<a href="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400">/tree-frog.jpg?width=500</a>

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=500)

> Note: It is not possible to upscale an image. When using a width parameter greater than the original image width, the image is returned at it's original width value.

## Height

Image height represents the height of the output image. The `height` or `h` parameter allows you to dynamically resize the image based on pixels values. If only the height is provided, then the image is scaled to the new dimension while retaining the original aspect ratio.

<a href="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?height=350">/tree-frog.jpg?height=350</a>

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?height=350)

> **Note:** It is not possible to upscale an image. When using a height parameter greater than the original image height, the image is returned at it's original height value.

## Width and height

When both the `width` and `height` parameters are provided, the image is resized so that it takes up as much space as possible within the bounding box defined by the given width and height parameters. The original aspect ratio is retained and all of the original image is visible.

<a href="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?height=350">/tree-frog.jpg?width=640&height=480</a>

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=640&height=480)