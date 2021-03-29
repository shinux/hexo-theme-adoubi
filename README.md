# hexo-theme-adoubi

another simple hexo theme. [online demo](https://sinux.icu)

![demo](demo.png)

## Installation

hexo-theme-adoubi developed with hexo 3.2

*plugin dependencies*:

- hexo-renderer-pug
- hexo-generator-feed
- hexo-toc

clone theme

    git clone https://github.com/shinux/hexo-theme-adoubi.git themes/adoubi

modify site config

    theme: adoubi

replace `themes/adoubi/sources/images/favicon.ico` with your own preference

upgrade

    cd themes/adoubi
    git pull origin master


## Display images in article:

if image located at site's `source/images` :

    <img src="/images/your-image.png">

> images will be limited to `max-width: 100%` compared to parent class `post-content`.

**NOTICE: hexo will use site's source preferentially**

## Display toc in article:

simply use `<!-- toc -->` on top of article. for more options see [hexo-toc](https://github.com/bubkoo/hexo-toc)

## Copyright

resources usage:

- SF Pro Text font
- normalize.css
- heti.css

Keep `Theme By Adoubi , Powered By Hexo.` in footer and do whatever you want.
