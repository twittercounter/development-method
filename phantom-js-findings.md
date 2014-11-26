# Phantom.js Findings #

In this document we document all the issues, bugs and solutins we've encountered using Phantom.js. Considering documenation for Phantom is muy mal, this document will hopefully speed up development and troubleshooting.

* * *

## CSS ##

- `opacity`: Seems to be supported, but doesn't seem to trigger font-smoothing or antialiasing, resulting in less than desirable resolution.
- `@font-face`: Does not seem to support `local()`, but `url()` works fine with full path urls.
- `@font-face`: So far only a single `font-weight` (`300`) is being rendered, while variety are being requested. Always renders `300`.

## HTML ##

- `<a>`: According to this issue ( ariya/phantomjs#10196 ) links aren't being generated on render.
