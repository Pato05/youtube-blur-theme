# youtube-blur-theme
A blur theme for youtube (may have unintended behaviour on white theme)

## How to add it
Download an [extension for your browser](https://google.com/search?q=inject+css+extension) capable of injecting css into youtube, and if possible, put <code>https://github.pato05mc.tk/youtube-blur-theme/style.css</code> as stylesheet.
If your extension only offers the possibility to put custom css, you can use the <code>@import</code> css directive.

## Blur is not working
If the blur effect is not working, you might need to enable the <code>backdrop-filter</code> css directive, on Firefox, you can do that by going into <code>about:config</code
and by enabling the <code>layout.css.backdrop-filter.enabled</code> flag.
