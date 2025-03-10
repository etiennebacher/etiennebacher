
I develop, contribute to, or maintain a few R packages related to various topics.

### Data manipulation

-   [polars](https://rpolars.github.io/): port of the Rust/Python [polars](https://pola.rs/)
    to R.

-   [tidypolars](https://tidypolars.etiennebacher.com/): get the power of `polars`
    with the syntax of the `tidyverse`. 

-   [datawizard](https://easystats.github.io/datawizard/): this package is
    part of the [`easystats`](https://easystats.github.io/easystats/) ecosystem.
    It provides many functions to manipulate data (similarly to what `dplyr` and
    `tidyr` do) and to perform various statistical transformation on variables
    (standardizing, winsorizing, normalizing, etc.).

### Package development & Tooling

-   [altdoc](https://altdoc.etiennebacher.com): use [docsify.js](https://docsify.js.org/#/),
    [docute](https://docute.org/), [mkdocs](https://www.mkdocs.org/), or [quarto](https://quarto.org/)
    to build a website for your R package documentation. This is meant to
    be an alternative to `{pkgdown}`.
-   [flir](https://flir.etiennebacher.com/): very fast package to find lints and automatically fix
    them based on an extensible list of rules.
-   [astgrepr](https://astgrepr.etiennebacher.com/): a package to parse and manipulate R code based on
    the [ast-grep](https://ast-grep.github.io/) Rust crate. This is the foundation on which `flint` is
    built. 

### R Shiny applications

-   [conductor](https://conductor.etiennebacher.com): create tours in Shiny
    apps. This uses [shepherd.js](https://shepherdjs.dev/) under the hood
    and provides similar functionalities as [`cicerone`](https://cicerone.john-coene.com/)
    and [`rintrojs`](https://carlganz.github.io/rintrojs/).

-   [prompter](https://prompter.etiennebacher.com): easily create
    tooltips in Shiny apps. It uses [hint.css](https://github.com/chinchang/hint.css)
    under the hood.

-   [shinyfullscreen](https://github.com/etiennebacher/shinyfullscreen):
    display HTML elements in fullscreen in Shiny apps. This uses
    [screenfull.js](https://github.com/sindresorhus/screenfull.js) under the hood.

---

While developing packages for R Shiny applications, I had some trouble trying to determine
if a Javascript library had already been adapted in R. Therefore, I
started a list of R packages that adapt Javascript libraries:
[awesome-R-JS-adaptation](https://github.com/etiennebacher/awesome-R-JS-adaptation). Feel
free to propose missing libraries.
