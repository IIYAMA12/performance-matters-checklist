# Performance Checklist

## Table of Contents

*   [Miscellaneous](#miscellaneous)
*   [Audits](#audits)
*   [HTTP optimisation](#http-optimisation)
    *   [HTTP/1](#http1)
    *   [HTTP/2](#http2)
*   [Caching](#caching)
*   [Minification](#minification)
    *   [Images](#images)
    *   [CSS](#css)
    *   [HTML](#html)
    *   [JavaScript](#javascript)
    *   [Fonts](#fonts)
*   [Perceived Performance](#perceived-performance)
*   [Performance](#performance)
    *   [Images](#images-1)
    *   [CSS](#css-1)
    *   [HTML](#html-1)
    *   [JavaScript](#javascript-1)
    *   [Fonts](#fonts-1)
*   [Backend optimisation](#backend-optimisation)

## Miscellaneous

*   Tip: Different profile / user in Chrome without extensions
*   Add some more points here...

## Audits

<details>
    <summary>Page load frames</summary>
    <details>
        <summary>Mobile</summary>
        <!-- <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/mobile/Schermafbeelding 2018-03-13 om 14.35.26.png" alt="State 1"> -->
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/mobile/Schermafbeelding 2018-03-13 om 14.36.16.png" alt="State 2">
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/mobile/Schermafbeelding 2018-03-13 om 14.36.18.png" alt="State 3">
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/mobile/Schermafbeelding 2018-03-13 om 14.36.50.png" alt="State 4">
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/mobile/Schermafbeelding 2018-03-13 om 14.36.54.png" alt="State 5">
    </details>
    <details>
        <summary>Laptop</summary>
        <!-- <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/mobile/Schermafbeelding 2018-03-13 om 14.40.33.png" alt="State 1"> -->
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/laptop/Schermafbeelding 2018-03-13 om 14.42.18.png" alt="State 2">
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/laptop/Schermafbeelding 2018-03-13 om 14.42.21.png" alt="State 3">
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/laptop/Schermafbeelding 2018-03-13 om 14.42.52.png" alt="State 4">
        <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/laptop/Schermafbeelding 2018-03-13 om 14.42.55.png" alt="State 5">
    </details>
</details>

## HTTP optimisation

<details>
    <summary>HTTP requests</summary>
    <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/requests/Screen Shot 2018-03-13 at 17.27.01.png" alt="State 5">
    <img src="https://iiyama12.github.io/performance-matters-checklist/readme-content/Webside-CMD-Amsterdam-performance-test/slow-loading/requests/Screen Shot 2018-03-13 at 17.27.32.png" alt="State 5">
</details>

### HTTP/1

*  Using as HTTP/2 might speed up the total download speed.

### HTTP/2

*   Not Served as HTTP/2.

## Caching

*   Add some more points here...

## Minification

*   Add some more points here...

### Images

*   Images with little detail and small colour pallet, are smaller and perform better with png format instead of jpg. If possible, use svg.

### CSS
*   Minify CSS

### HTML
*   Minify HTML

### JavaScript

*   Minify JS


### Fonts
* (some) Fonts maybe loaded later, since there are 11 requests for them.


## Perceived Performance

*   ...

## Performance

*   Reduce amount of classes and attributes in html

### Images

*   SVG's are smaller but they do not render always faster than other formats. Especially when they are very complex. Render speed is also included with the load time of content.

### CSS

*   Remove un-used CSS.
*   Remove prefixes that are already global supported.

### HTML

*   Add some more points here...

### JavaScript

*   No jQuery
*   

### Fonts

*   ...

## Backend optimisation

*   ...
