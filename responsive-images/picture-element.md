# Picture

## Art direction

Using different images or the same image that have been cropped to fit a particular screen's features can help in communicating a message effectively.

```html
<picture>
      <!-- Show a portrait cropped version of the image in grayscale for viewports up to 320px -->
      <source media="(max-width: 320px)" 
              srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=240&h=320&fit=crop&e=grayscale 240w">

      <!-- Show a portrait cropped version of the image for viewports up to 480px -->
      <source media="(max-width: 480px)" 
              srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=240&h=320&fit=crop 240w">

      <!-- Show a traditional 4:3 crop of the image for viewports up to 640px -->
      <source media="(max-width: 640px)" 
              srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=640&h=320&fit=crop 640w">

      <!-- Show a letterbox crop of the image for viewports up to 1920px -->
      <source media="(max-width: 1920px)" 
              srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=1024&h=450&fit=crop-bottom 1024w">

      <!-- Show a tighter letterbox crop of the image for viewports larger than 1921px -->
      <source media="(min-width: 1921px)" 
              srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=1920&h=600&fit=crop 1920w">

      <img src="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=240&h=320&fit=crop" 
           alt="Dainty tree frog">
</picture>
```

<p data-height="328" data-theme-id="dark" data-slug-hash="pQgjXE" data-default-tab="html,result" data-user="zengenti" data-pen-title="Responsive Images - Art Direction" data-preview="true" class="codepen">See the Pen <a href="https://codepen.io/zengenti/pen/pQgjXE/">Responsive Images - Art Direction</a> by Zengenti (<a href="https://codepen.io/zengenti">@zengenti</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

[View CodePen](https://codepen.io/zengenti/pen/pQgjXE)