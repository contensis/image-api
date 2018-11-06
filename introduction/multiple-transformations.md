# Multiple transformations

Transformations can be chained together to apply multiple changes to an image.

## Example

`https://preview-imageapi.cloud.contensis.com/image-library/Stock-Images/artists-works.jpg`

### Transformations

* ?width=200
* ?width=200?quality=50
* ?width=200?quality=50?format=webp

### Transformation applied

#### Width

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=500)

```json
?width=500
```



#### Width and quality

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=300&quality=50)

```json
?width=300&quality=50
```



#### Width, quality and grayscale effect

![](https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=400&quality=50&effect=grayscale)

```json
?width=400&quality=50&effect=grayscale
```