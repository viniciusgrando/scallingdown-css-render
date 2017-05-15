# Scalling Down Css Render

Condition for rendering scaled images via css

## Preview

<img width="572" src="https://raw.githubusercontent.com/viniciusgrando/scallingdown-css-render/master/bandaf.png" alt="Demo">

## Global values
``` html
image-rendering: inherit;
image-rendering: initial;
image-rendering: unset;
```

## Formal syntax

``` html
auto | crisp-edges | pixelated
```

## Code

``` html
image-rendering: -moz-crisp-edges;         /* Firefox */
image-rendering:   -o-crisp-edges;         /* Opera */
image-rendering: -webkit-optimize-contrast;/* Webkit (non-standard naming) */
image-rendering: crisp-edges;
-ms-interpolation-mode: nearest-neighbor;  /* IE (non-standard property) */
```

## Values

#### Auto

Default value, the image should be scaled with an algorithm that maximizes the appearance of the image. In particular, scaling algorithms that "smooth" colors are acceptable, such as bilinear interpolation. This is intended for images such as photos. Since version 1.9 (Firefox 3.0), Gecko uses bilinear resampling (high quality)

#### Crisp-edges

The image must be scaled with an algorithm that preserves contrast and edges in the image, and which does not smooth colors or introduce blur to the image in the process. This is intended for images such as pixel art.

#### Pixelated

When scaling the image up, the "nearest neighbor" or similar algorithm must be used, so that the image appears to be composed of large pixels. When scaling down, this is the same as 'auto'.

## Browser Support

| <img src="https://clipboardjs.com/assets/images/chrome.png" width="48px" height="48px" alt="Chrome logo"> | <img src="https://clipboardjs.com/assets/images/edge.png" width="48px" height="48px" alt="Edge logo"> | <img src="https://clipboardjs.com/assets/images/firefox.png" width="48px" height="48px" alt="Firefox logo"> | <img src="https://clipboardjs.com/assets/images/ie.png" width="48px" height="48px" alt="Internet Explorer logo"> | <img src="https://clipboardjs.com/assets/images/opera.png" width="48px" height="48px" alt="Opera logo"> | <img src="https://clipboardjs.com/assets/images/safari.png" width="48px" height="48px" alt="Safari logo"> |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 49+ ✔ | 14+ ✔ | 52+ ✔ | 11+ ✔ | 44+ ✔ | 10+ ✔ |
