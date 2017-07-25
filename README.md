An on-line open manuscript reviewing ecological methods for dealing with observation error and possible connections to veterinary epidemiology.

The html version is available at https://atyre2.github.io/vet-obserror, and a pdf version at https://atyre2.github.io/vet-obserror/_main.pdf.

The key is the `site` setting in `index.Rmd`. If you want to build the book in RStudio, just click the `Build Book` button in the `Build` pane, otherwise call the function in R:

```r
bookdown::render_book('index.Rmd', 'all')
```
