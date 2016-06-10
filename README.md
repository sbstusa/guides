# Some guides to help us do our work


## On Randomization Inference

[HTML Version of the guide](http://htmlpreview.github.io/?https://github.com/sbstusa/guides/blob/master/Randomization-Inference-primer-for-SBST.html)


# How we make the guides?

We tend to write them in R markdown format. We make the html and/or pdf versions using either the "Knit to HTML"/"Knit to PDF" buttons in RStudio or using the following commands in R:

```
library(rmarkdown)
render("thedoc.Rmd",output_format=html_document())
render("thedoc.Rmd",output_format=pdf_document())
```


