# assignment-7
# Brief review of the Rpackage `{magick}`

### Package title
magick

### Location
CRAN: `install.packages("magick")` also on GitHub (for development): https://github.com/ropensci/magick

### Vignettes
The package has a vigniette that quickly, intuitively, and with a bit of humor, demostrates the basic functionality of the package. 
https://cran.r-project.org/web/packages/magick/vignettes/intro.html

### Applications
Images of all types can be easily cropped, combined, and edited within R. Can also be used to construct and deconstruct gifs.

### Review
Although this package is used for advanced image manipulation, it is quite simple to use. I like it because it does precise image processing and annotating with simple functions. I discovered `{magick}` when I was unable to use another favorite package (`{patchwork}`) to compile a multi-panel plot. In my case, `{patchwork}` could not recognize ternary diagrams produced by `{ggtern}` because the usual ggplot geometry (ie x-y coordinates) had been overwritten and lost. With a few simple commands, I was able to take my two plots and put them together into a single figure with A,B annotation. The package `{magick}` allows for precise image manipulation that you might do with PowerPoint or Photoshop, but in an R code structure, which makes any steps taken to alter figures/images reproducible. With this package it is easy combine different file types (png, jpg, etc), cropping, resizing, layering, etc. I like that you store images as objects, and then combine them together in a number of different ways, and that you can see what you are doing the Plots pane of RStudio. I also like that you can use pipe syntax to make your code easily readable. 

The vignettes and tutorials make it surprisingly simple to use. The main help page is organized extremely well, with **pictures**, so each thing you wish to do (re-size, stack, overlay, annotate, etc) it is simple to find at a glance by scaning the help page for pictures of what you may be trying to do with your images.

Overall, I think this package is amazing, I highly recommend it, and it can do far more than I've used it for!
