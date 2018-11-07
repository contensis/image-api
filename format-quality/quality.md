# Image quality

The `quality` or `q` parameter provides control over the compression level of images. The value is an integer between 0 and 100. A lower number represents a lower-quality output image with a smaller file size and vice-versa.

```http
https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400&quality=50
```

## Example

Quality | Image | File size
---------|----------|---------
[Original (Resized)](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400) | ![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400) | 16.37KB
[?quality=50](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400&quality=50) | ![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400&quality=50) | 9.70KB
[?quality=20](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400&quality=20) | ![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400&quality=20) | 7.86KB

