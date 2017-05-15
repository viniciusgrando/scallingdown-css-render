# Scalling Down Css Render

Condition for rendering scaled images via css

## Code Render

``` html
image-rendering: -moz-crisp-edges;         /* Firefox */
image-rendering:   -o-crisp-edges;         /* Opera */
image-rendering: -webkit-optimize-contrast;/* Webkit (non-standard naming) */
image-rendering: crisp-edges;
-ms-interpolation-mode: nearest-neighbor;  /* IE (non-standard property) */
