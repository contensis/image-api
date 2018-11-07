# Exact

An exact crop defines a region of the original image with a given width and height and coordinates where the crop should be started.

The value for crop is four relative values representing the `width` and `height` and the starting coordinates of `x` and `y` all separated by commas. All the values must be greater than or equal to 0.

<figure>
    <img src="https://zenhub.zengenti.com/image-examples/tree-frog-crop-combined.jpg?width=1000&quality=50" alt="Example crop area for exact crop">
    <figcaption>The rectangle outlined in the image will be used for the crop, and is defined by the following parameters <code>crop=1500,1500,2300,1280</code></figcaption>
</figure>

---

## An exact crop of 1500x1500 from specific coordinates

!INCLUDE "../examples/crop-exact.html"
