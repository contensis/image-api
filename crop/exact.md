# Exact

Extract a region of the original image with a given width and height and the exact coordinates where the crop should be started.

By default, the entire image is used as the area for processing. The crop parameter selects a sub-region of the source image to use for processing before applying other resize operations.

The value for crop is four relative values representing the width (w) and height (h) and the starting coordinates of x and y all separated by commas. All the values must be greater than or equal to 0.

```http
https://zenhub.zengenti.com/image-examples/tree-frog.jpg?crop=1500,1500,2300,1280
```

![](https://zenhub.zengenti.com/image-examples/tree-frog-crop-combined.jpg?width=1000&quality=50)

## Crop by dimensions from specific x,y coordinates
!INCLUDE "../examples/crop-exact.html"
