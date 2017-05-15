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
