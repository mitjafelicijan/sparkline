# Simple SVG Sparklines

![Preview](https://github.com/mitjafelicijan/sparkline/assets/296714/bffe023d-4e9a-461c-976c-7e78b296b14c)

Add `sparkline.js` to your HTML file and use proper data attributes and that is about it.

| Attribute | Description | Default Value |
|-----------|-------------|---------------|
| data-sparkline | If sparkline is enabled on this element | None |
| data-points | List of numbers / data | [] |
| data-width | Width of the container in px | 100 |
| data-height | Height of the container in px | 30 |
| data-gap | Gap between the bars in px | 5 |
| data-color | Color of the bars in HEX or color name | gray |

**Example**

```html
<div data-sparkline="true" data-points="6,2,3,4,5" data-width="300" data-height="50" data-gap="15" data-color="#ff0000"></div>
<script src="sparkline.js" defer></script>
```

Check `index.html` for more examples.

To create minified version of `sparkline.js` use `npx minify sparkline.js > sparkline.min.js`.
