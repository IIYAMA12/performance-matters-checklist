# Performance Checklist

## Table of Contents

-   [Miscellaneous](#miscellaneous)
-   [Audits](#audits)
-   [HTTP optimisation](#http-optimisation)
    -   [HTTP/1](#http1)
    -   [HTTP/2](#http2)
-   [Caching](#caching)
-   [Minification](#minification)
    -   [Images](#images)
    -   [CSS](#css)
    -   [HTML](#html)
    -   [JavaScript](#javascript)
    -   [Fonts](#fonts)
-   [Perceived Performance](#perceived-performance)
-   [Performance](#performance)
    -   [Images](#images-1)
    -   [CSS](#css-1)
    -   [HTML](#html-1)
    -   [JavaScript](#javascript-1)
    -   [Fonts](#fonts-1)
-   [Backend optimisation](#backend-optimisation)

## Miscellaneous

-   Tip: Different profile / user in Chrome without extensions

## Audits

## HTTP optimisation

### HTTP/1

*  Using as HTTP/2 might speed up the total download speed.

### HTTP/2

## Caching

## Minification

### Images

*   Images with little detail and small colour pallet, are smaller and perform better with png format instead of jpg. If possible, use svg.

### CSS

*   Reduce selectors
*   Minify CSS

### HTML

*   Reduce HTML wrapper elements
*   Minify HTML

### JavaScript

*   Reduce function calls
*   Minify JS

### Fonts

*   Load fonts last and use the swap css property to keep the text readable.

## Perceived Performance

## Performance

*   Reduce amount of classes and attributes in html

### Images

*   SVG's are smaller but they do not render always faster than other formats. Especially when they are very complex. Render speed is also included with the load time of content.

### CSS
*   Remove un-used CSS.

*   Remove prefixes that are already global supported.

### HTML

### JavaScript

*   Remove jQuery

### Fonts

*   Do not use custom fonts if not needed.

## Backend optimisation

*   Make use of buffers to reduce database requests.