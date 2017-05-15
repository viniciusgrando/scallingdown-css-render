# Scalling Down Css Render

Condition for rendering scaled images via css

## Preview

<img width="572" src="https://raw.githubusercontent.com/viniciusgrando/scallingdown-css-render/master/bandaf.png" alt="Demo">

## Code

``` html
image-rendering: -moz-crisp-edges;         /* Firefox */
image-rendering:   -o-crisp-edges;         /* Opera */
image-rendering: -webkit-optimize-contrast;/* Webkit (non-standard naming) */
image-rendering: crisp-edges;
-ms-interpolation-mode: nearest-neighbor;  /* IE (non-standard property) */

## Browser Support

| <img src="https://clipboardjs.com/assets/images/chrome.png" width="48px" height="48px" alt="Chrome logo"> | <img src="https://clipboardjs.com/assets/images/edge.png" width="48px" height="48px" alt="Edge logo"> | <img src="https://clipboardjs.com/assets/images/firefox.png" width="48px" height="48px" alt="Firefox logo"> | <img src="https://clipboardjs.com/assets/images/ie.png" width="48px" height="48px" alt="Internet Explorer logo"> | <img src="https://clipboardjs.com/assets/images/opera.png" width="48px" height="48px" alt="Opera logo"> | <img src="https://clipboardjs.com/assets/images/safari.png" width="48px" height="48px" alt="Safari logo"> |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 49+ ✔ | 14+ ✔ | 52+ ✔ | 11+ ✔ | 44+ ✔ | 10+ ✔ |
