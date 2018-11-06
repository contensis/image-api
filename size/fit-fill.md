# Fit fill

When the `fit=fill` parameter is used in conjunction with the `width` and `height` parameters then the image will be stretched to fit the constraining dimensions exactly. The resulting image will fit within the width and height boundaries without cropping or distorting the image. The remaining space is filled with a background color specified by the `background` or `bg` parameter hex value. The resulting image will match the constraining dimensions.


```http
https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=600&height=600&fit=fill&bg=c0c0c0
```

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=600&height=600&fit=fill&bg=c0c0c0)