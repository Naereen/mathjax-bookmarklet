# *MathJax Bookmarklet*

*MathJax Bookmarklet* is a [bookmarklet](https://en.wikipedia.org/wiki/Bookmarklet) for rendering TeX/LaTeX and MathML notation on pages dynamically using the [MathJax](http://www.mathjax.org/) library.

Pages don't have to include `mathjax.js`.
The library is included and configured dynamically. The LaTeX preprocessor will render equations delimited by `$...$` or by `\(...\)` (for inline maths) and `\[...\]` or `$$...$$` for display math.

The ASCIIMathML preprocessor will render equations delimited by ``` `...` ```.

*Note: This bookmarklet will also try to render math notation inside iframes. This will be successfully executed only on iframes on the same domain because cross-domain policies don't support modification of iframe content from other domains*.

## Install
Install the bookmarklet **[HERE](https://naereen.github.io/mathjax-bookmarklet/)**.

## Build?
Minify the bookmarklet from bookmarklet.js by using `uglifyjs bookmarklet.js -m`. (with UglifyJS2)

---

### :scroll: License ? [![GitHub license](https://img.shields.io/github/license/Naereen/mathjax-bookmarklet.svg)](https://github.com/Naereen/mathjax-bookmarklet/blob/master/LICENSE)
This (small) repository are published under the terms of the [MIT license](http://lbesson.mit-license.org/) (file [LICENSE.txt](LICENSE.txt)).
© [Lilian Besson](https://GitHub.com/Naereen), 2018.

[![Maintenance](https://img.shields.io/badge/Maintenu%3F-oui-green.svg)](https://GitHub.com/Naereen/mathjax-bookmarklet/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/mathjax-bookmarklet)
[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/mathjax-bookmarklet/README.md?pixel)](https://GitHub.com/Naereen/mathjax-bookmarklet/)
[![made-with-mathjax](https://img.shields.io/badge/Made%20with-MathJax-1f425f.svg)](https://www.mathjax.org/)
[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)

[![ForTheBadge built-with-swag](http://ForTheBadge.com/images/badges/built-with-swag.svg)](https://GitHub.com/Naereen/)

[![ForTheBadge uses-js](http://ForTheBadge.com/images/badges/uses-js.svg)](http://ForTheBadge.com)
[![ForTheBadge uses-badges](http://ForTheBadge.com/images/badges/uses-badges.svg)](http://ForTheBadge.com)
[![ForTheBadge uses-git](http://ForTheBadge.com/images/badges/uses-git.svg)](https://GitHub.com/)
