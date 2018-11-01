# Srcset

## Resolution-based selection

[W3C - Resolution-based selection](http://usecases.responsiveimages.org/#resolution-based-selection)

```html
<img src="https://preview-imageapi.cloud.contensis.com/api/image/1027?width=240"
     alt="A lady holding a flat white in a coffee shop"
    srcset="https://preview-imageapi.cloud.contensis.com/api/image/1027?width=1024 1024w,
            https://preview-imageapi.cloud.contensis.com/api/image/1027?width=960 960w,
            https://preview-imageapi.cloud.contensis.com/api/image/1027?width=480 480w,
            https://preview-imageapi.cloud.contensis.com/api/image/1027?width=320 320w">
```

## Viewport based selection

[W3C - Viewport-based selection](http://usecases.responsiveimages.org/#viewport-based-selection)

```html
<img src="https://preview-imageapi.cloud.contensis.com/api/image/1027?width=240"
         alt="A lady holding a flat white in a coffee shop"
         srcset="https://preview-imageapi.cloud.contensis.com/api/image/1027?width=1024 1024w,
                 https://preview-imageapi.cloud.contensis.com/api/image/1027?width=960 960w,
                 https://preview-imageapi.cloud.contensis.com/api/image/1027?width=480 480w,
                 https://preview-imageapi.cloud.contensis.com/api/image/1027?width=320 320w,
                 https://preview-imageapi.cloud.contensis.com/api/image/1027?width=200&effect=grayscale 200w"
         sizes="(max-width: 320px) 200px,
                (max-width: 480px) 420px,
                (min-width: 2560px) 1024px,
                800px">
```


## Device-pixel-ratio-based selection

[W3C - Device-pixel-ratio-based selection](http://usecases.responsiveimages.org/#device-pixel-ratio-based-selection)

```html
<img src="https://preview-imageapi.cloud.contensis.com/api/image/1027?width=300"
         alt="A lady holding a flat white in a coffee shop"
    srcset="https://preview-imageapi.cloud.contensis.com/api/image/1027?width=900 3x
                    https://preview-imageapi.cloud.contensis.com/api/image/1027?width=600 2x,
                    https://preview-imageapi.cloud.contensis.com/api/image/1027?width=450 1.5x,
                    https://preview-imageapi.cloud.contensis.com/api/image/1027?width=300">
```


