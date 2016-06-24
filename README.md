# Some guides to help us do our work


## On Re-Analysis

[HTML Version of the guide](http://htmlpreview.github.io/?https://github.com/sbstusa/guides/blob/master/reanalysis.html)

## On Randomization Inference

[HTML Version of the guide](http://htmlpreview.github.io/?https://github.com/sbstusa/guides/blob/master/Randomization-Inference-primer-for-SBST.html)


## On Randomization and Blocking 

[HTML Version of the guide](http://htmlpreview.github.io/?https://github.com/sbstusa/guides/blob/master/randomization.html)

# How we make the guides?

We tend to write them in R markdown format. We make the html and/or pdf versions using either the "Knit to HTML"/"Knit to PDF" buttons in RStudio or using the following commands in R:

```
library(rmarkdown)
render("thedoc.Rmd",output_format=html_document())
render("thedoc.Rmd",output_format=pdf_document())
```

# Other guides and inspirations

If you have a question that we haven't yet covered here, you can feel free to raise it in the Issues. First, however, you might check out the [EGAP methods guides]() or Alex Coppock's [guide to the R randomizr package](http://www.columbia.edu/~ac3242/randomizr_vignette.html) and Don Green and Winston Lin's (standard operating procedures)[https://github.com/acoppock/Green-Lab-SOP].

