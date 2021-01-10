# Hugo Theme ZozoMod

[![GitHub](https://img.shields.io/github/license/hanrong-zhang/hugo-ZozoMod.svg?color=4664DA&style=flat-square)](https://github.com/hanrong-zhang/hugo-ZozoMod/blob/master/LICENSE)

A Hugo blog theme based on [Zozo](https://github.com/varkai/hugo-theme-zozo). Zozo is a port of [Aragaki](https://github.com/PCDotFan/Aragaki), which includes style referenced from [菩提树下](https://blog.caicai.me/) and some functions referenced from [Even](https://github.com/olOwOlo/hugo-theme-even).

**[Demo](https://zozo-mod.web.app)**

## Features

- Responsive
- Syntax highlighting with highlightjs
- MathJax and KaTeX
- Social media links
- Tags page and Categories page
- Archive page
- Disqus and [Valine](https://valine.js.org/en/index.html) comment-system
- Fancybox
- GoogleAnalytics

## Designs

- Paginations for index page, post single pages, and archive page
- Displays front matter `description` as post summary, prepends `description` content to post content

## Installation

Clone this repository to `themes` folder.  
Edit your site config following `exampleSite/config.toml`.  
Follow [Quick Start](https://gohugo.io/getting-started/quick-start/) and navigate to your new site.


## Customization

### About Page

Introduce yourself on the About Page by editing `/content/about.md`.

### Archive Pagination

Change the number of articles listed on an archive page by editing the number in the first line of `themes/ZozoMod/layouts/_default/list.html`

### Social Link Icons

Edit your social icons by modifying entries in the social section of `config.toml`.  
[Remix icon](https://remixicon.com/) is used in this theme.

## Shortcodes

This theme provides `img` shortcodes.

```markdown
{{< img src="path/to/xxx.png" >}}
```

## Math Typesetting

This theme supports MathJax and KaTeX. By default, it uses KaTeX and MathJax is turned off. You can change your preference in `config.toml`. Under `[params]`, set `enableMathJax` and `enableKaTeX` to support desired math typesetting.

## License

This theme is released under [MIT](https://github.com/hanrong-zhang/hugo-ZozoMod/blob/master/LICENSE) License.

## Acknowledgements

- [Varkai](https://varkai.com/)
- [Aragaki](https://github.com/PCDotFan/Aragaki)
- [菩提树下](https://blog.caicai.me/)
- [olOwOlo](https://olowolo.com/)
- [Hugo theme Jane (KaTeX reference)](https://github.com/xianmin/hugo-theme-jane/blob/68e0de4273df61045f5a6edd5ecd5a1703e32cf9/layouts/partials/scripts.html)

