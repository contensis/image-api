---
description: This article shows some examples of how you can use the the Image API with the srcset attribute.
---

# Srcset

## Resolution-based selection

Developers generally want to provide the same image in multiple resolutions, so that high-res devices can get the optimum image for a given resolution, while low-resolution devices can avoid wasting time and bandwidth downloading overly-large files.


```html
<img src="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=240"
     alt="A small tree frog"
    srcset="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=1024 1024w,
            https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=960 960w,
            https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=480 480w,
            https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=320 320w">
```

<p data-height="450" data-theme-id="dark" data-slug-hash="vQLLjY" data-default-tab="html,result" data-user="zengenti" data-pen-title="Resolution-based selection" data-preview="true" class="codepen">See the Pen <a href="https://codepen.io/zengenti/pen/vQLLjY/">Resolution-based selection</a> by Zengenti (<a href="https://codepen.io/zengenti">@zengenti</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

[View CodePen](https://codepen.io/zengenti/pen/vQLLjY/)

## Viewport based selection

Image dimensions in responsive layouts tend to vary according to the size of the viewport. This often results in images with large dimensions (e.g. 2x or more times the size of the viewport) being sent to browsers with a narrow viewport, which are then resized by the browser to fit the design. Ideally, developers should serve images that match the user's viewport dimensions.

For example, a 1000px wide image might be appropriate as a 1x image when used to fill the background of the page, but it’s far too large to use for the same purpose on a 320px wide screen. On a screen that small, it’s more like a 2x or 3x image. In other words, the same image might be applicable to multiple viewport sizes, but at different effective resolutions.

To avoid sending excess data, developers can use `srcset` along with the `size` attribute in order to send images that more closely match the size of the viewport.

```html
<img src="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=240"
         alt="A small tree frog"
         srcset="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=1024 1024w,
                 https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=960 960w,
                 https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=480 480w,
                 https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=320 320w,
                 https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=200&effect=grayscale 200w"
         sizes="(max-width: 320px) 200px,
                (max-width: 480px) 420px,
                (min-width: 2560px) 1024px,
                800px">
```

<p data-height="450" data-theme-id="dark" data-slug-hash="JeGGaz" data-default-tab="html,result" data-user="zengenti" data-pen-title="Viewport-based selection" data-preview="true" class="codepen">See the Pen <a href="https://codepen.io/zengenti/pen/JeGGaz/">Viewport-based selection</a> by Zengenti (<a href="https://codepen.io/zengenti">@zengenti</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

[View CodePen](https://codepen.io/zengenti/pen/JeGGaz/)

## Device-pixel-ratio-based selection

Many new devices offer high resolution displays often branded with terms such as retina, FHD or QHD. These devices have a device-pixel-ratio greater than one. The higher the pixel density, the more pixels an image needs to have to look good. Higher image resolutions are required to reduce visual artifacts resulting from compression. Display density descriptors are a helpful approach when you know the types of devices you are targeting.

```html
<img src="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=300"
        alt="A dainty tree frog"
        srcset="https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=900 3x
                https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=600 2x,
                https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=450 1.5x,
                https://zenhub.zengenti.com/image-examples/tree-frog.jpg?width=300">
```

<p data-height="450" data-theme-id="dark" data-slug-hash="gQPPZM" data-default-tab="html,result" data-user="zengenti" data-pen-title="Device-pixel-ratio-based selection" data-preview="true" class="codepen">See the Pen <a href="https://codepen.io/zengenti/pen/gQPPZM/">Device-pixel-ratio-based selection</a> by Zengenti (<a href="https://codepen.io/zengenti">@zengenti</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

[View CodePen](https://codepen.io/zengenti/pen/gQPPZM/)