
<!-- README.md is generated from README.Rmd. Please edit that file -->

# newsies

🗞 Newsletter automation inspired by the [rOpenSci
Newsletter](https://ropensci.org/news/), and Maëlle Salmon’s post on
same, [“How we curate our monthly
newsletter”](https://ropensci.org/blog/2021/06/24/news-meta/) (24 June,
2021).

Resources from above:

-   [Hugo
    archetype](https://github.com/ropensci/roweb3/tree/master/archetypes/newsletter)
    for parameterized R Markdown report (view
    [index.md](https://github.com/ropensci/roweb3/blob/master/archetypes/newsletter/index.md)).  
-   [rOpenSci Package Registry](https://github.com/ropensci/roregistry)
    (n.b. this is mainly so we can see what information/the data
    structure rOpenSci feeds into its “report”/newsletter).  
-   [makeregistry](https://github.com/ropensci-org/makeregistry) - how
    the above registry is generated.  
-   [codemetar](https://github.com/ropensci/codemetar): an R package for
    generating and working with codemeta, as described at
    <https://codemeta.github.io>.  
-   [rOpenSci full-content
    newsfeed](https://ropensci.org/rbloggers/index.xml) (figure out why
    [their
    layout](https://github.com/ropensci/roweb3/blob/master/themes/ropensci/layouts/rbloggers/rss.xml)
    looks so different to
    [ours](https://www.tidyverse.org/blog/index.xml); see also their
    non-full-content [RSS
    feed](https://ropensci.org/tags/newsletter/index.xml) which I think
    is generated from the [outputs
    section](https://github.com/ropensci/roweb3/blob/04b4fe7c3bf95cc805ecebe2aca29e849dc40af5/config.toml#L37-L41)
    of their theme toml file).  
-   [Newsletter
    checklist](https://github.com/ropensci/roweb3#newsletter).  
-   [Newsletter tag page](https://ropensci.org/tags/newsletter/).

Other resources:

-   [`build_news()`
    code](https://github.com/r-lib/pkgdown/blob/master/R/build-news.R)
    from pkgdown.  
-   [tidymodels
    newsletter](https://www.tidyverse.org/blog/2021/03/tidymodels-2021-q1/).  
-   [New in
    knitr](https://blog.rstudio.com/2021/04/20/knitr-fig-alt/).  
-   See also (now defunct) RStudio internal newsletter updates.

## Notes

-   Per conversation with Alison, it might be useful to do this for all
    OSS packages, since it’s already going to be fairly long. We could
    host it on pkgs.rstudio.com.  
-   Based on running this [pkgreport
    script](https://github.com/batpigandme/pkgreport/blob/conn/scripts/overview.R),
    there are over 270 repos we cover even *without* adding anything
    from R Markdown, etc.
