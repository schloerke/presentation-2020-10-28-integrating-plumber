# Expanding R Horizons: Integrating R with Plumber APIs

Talk given by James Blair and Barret Schloerke at RStudio Webinar, 2020-10-28.

Video: [James Blair & Barret Schloerke | Integrating R with Plumber APIs | RStudio (2020)](https://opensource.posit.co/resources/videos/2021-03-01_james-blair-barret-schloerke-integrating-r-with-plumber-apis-rstudio-2020/)

## Slides

* PDF: [presentation-2020-10-30-integrating-plumber.pdf](presentation-2020-10-30-integrating-plumber.pdf)

## Demo APIs

Example `plumber` APIs used throughout the talk, in [`plumber/`](plumber):

* [`plumber-penguin.R`](plumber/plumber-penguin.R) — end-to-end Palmer Penguins species prediction API
* [`plumber-sync.R`](plumber/plumber-sync.R) — synchronous API example
* [`plumber-future.R`](plumber/plumber-future.R), [`plumber-future-2.R`](plumber/plumber-future-2.R), [`plumber-future-full.R`](plumber/plumber-future-full.R) — async execution with `future`
* [`plumber-future-pkg-example.R`](plumber/plumber-future-pkg-example.R) — async example packaged as a plumber router
* [`fib.R`](plumber/fib.R), [`calc.R`](plumber/calc.R) — basic route examples
* [`pipe/entrypoint.R`](plumber/pipe/entrypoint.R), [`rapidoc/entrypoint.R`](plumber/rapidoc/entrypoint.R) — router entrypoints, including RapiDoc-based docs

## Abstract

In this webinar we focus on using the `plumber` package as a tool for integrating R with other frameworks and technologies. `plumber` is a package that converts your existing R code to a web API using unique one-line comments. Example use cases are used to demonstrate the power of APIs in data science and to highlight new features of the `plumber` package. Finally, we look at methods for deploying `plumber` APIs to make them widely accessible.

## Resources

* [`plumber` webpage](https://www.rplumber.io/)
* [`plumber` on GitHub](https://github.com/rstudio/plumber)
* [`plumberExamples`](https://github.com/sol-eng/plumberExamples)
* [`plumberDeploy`](https://github.com/meztez/plumberDeploy)
* [`rapidoc`](https://github.com/meztez/rapidoc)
* [RStudio webinars](https://github.com/rstudio/webinars)
* [RStudio Community — plumber tag](https://community.rstudio.com/tag/plumber)
* [rstudio.com/conference](https://rstudio.com/conference/)
