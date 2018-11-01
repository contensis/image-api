# Picture

## Art direction

[W3C - Art direction](http://usecases.responsiveimages.org/#art-direction)

```html
<picture>
     
    <source media="(max-width: 480px)"
            srcset="https://preview-imageapi.cloud.contensis.com/api/image/1027?w=480&effect=grayscale">
    <source media="(max-width: 1400px)"
            srcset="https://preview-imageapi.cloud.contensis.com/api/image/1027?crop=3888,2753,0,1615&width=1400">
    <source media="(min-width: 1920px)"
            srcset="https://preview-imageapi.cloud.contensis.com/api/image/1027?crop=3888,1239,0,2322&width=2560">
     
    <img src="https://preview-imageapi.cloud.contensis.com/api/image/1027?crop=3888,2753,0,1615&width=1400"
             alt="A lady holding a flat white in a coffee shop">
</picture>
```