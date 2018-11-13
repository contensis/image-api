# Picture

## Art direction

Using different images or the same image that have been cropped to fit a particular screen's features can help in communicating a message effectively.

```html
<picture>

        <source media="(max-width: 320px)"
                srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=240&h=320&fit=crop&e=grayscale 240w">

        <source media="(max-width: 480px)"
                srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=240&h=320&fit=crop 240w">

        <source media="(max-width: 640px)"
                srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=640&h=320&fit=crop 640w">

        <source media="(max-width: 1920px)"
                srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=1024&h=450&fit=crop-bottom 1024w">

        <source media="(min-width: 1921px)"
                srcset="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=1920&h=600&fit=crop 1920w">

        <img src="https://preview-master.cloud.contensis.com/image-examples/tree-frog.jpg?w=240&h=320&fit=crop"
                alt="Dainty tree frog">
</picture>
```

<p data-height="328" data-theme-id="dark" data-slug-hash="pQgjXE" data-default-tab="html,result" data-user="zengenti" data-pen-title="Responsive Images - Art Direction" data-preview="true" class="codepen">See the Pen <a href="https://codepen.io/zengenti/pen/pQgjXE/">Responsive Images - Art Direction</a> by Zengenti (<a href="https://codepen.io/zengenti">@zengenti</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
