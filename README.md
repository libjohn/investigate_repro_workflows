# README

<!-- badges: start -->

<!-- badges: end -->

-   Investigating [Posit's](https://posit.co) and Charlotte Wickham's [**Quarto Manuscript** project](https://quarto.org/docs/manuscripts/)

## Get started

1.  In CLI (e.g. RStudio Terminal, PowerShell, Bash, etc.): `quarto create` \> `project` \> `manuscript`
    -   Identify LFS path / location
2.  Go to that location; double-click \<new_proj_name\>.Rproj file (if using R)
3.  `useths::use_git()`
4.  in `_quarto.yml` change `jats: default` to `pdf: default`
    -   JATS makes this cool MECA Bundle but I found that harder to deal with in a training context; YMMV. I think only some authors will need that. Therefore KISS.

## [Publish](https://quarto.org/docs/publishing/): a select list of options

-   drop-and-drag into **netlify**.com: <https://vermillion-sunshine-2799f6.netlify.app/>

-   **quarto.pub**

    -   login to https://quarto.pub
    -   In RStudio terminal: `quarto publish` \> `Quarto Pub`

-   Publishing to **GitHub Pages** is also possible. (Only I personally find that option harder. YMMV.)
