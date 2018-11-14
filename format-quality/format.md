---
description: This article outlines how you can change the image format of an image using the Image API.
---

# Output format

The format `format` or `f` parameter enables the source image to be converted from one format to another. Valid values for the `format` parameter are gif, png, jpg, and webp.

The source image can be any of the following image formats: gif, png, jpeg, and webp.

---

## PNG

The PNG file format is a lossless format. It does support transparency. It does not support animation.

The PNG file format is a common graphics format, often used for application assets such as logos and icons.

!INCLUDE "../examples/format-png.html"

---

## JPG

JPEG is a lossy format. It does not support transparency or animation.

JPEG is one of the most common formats on the web. It excels at displaying photographs. See the [quality](quality.md) parameter for controlling the quality of the image.

!INCLUDE "../examples/format-jpg.html"

---

## WebP

The WebP format browser support is currently limited. For a list of browsers that support WebP, please see the [WebP section](https://caniuse.com/#feat=webp) on caniuse.com.

If you choose to use the WebP format and the browser does not support it, we'll return a JPG in place of the WebP.

!INCLUDE "../examples/format-webp.html"