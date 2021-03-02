# assignment-7
# Brief review of the Rpackage `magick`

### Package title
magick

### Location
CRAN: `install.packages("magick")` also on GitHub (for development): https://github.com/ropensci/magick

### Vignette(s)
The package has a vigniette that quickly, intuitively, and with a bit of humor, demostrates the basic functionality of the package. 
https://cran.r-project.org/web/packages/magick/vignettes/intro.html

### Application(s)
Images of all types can be easily cropped, combined, and edited within R. Can also be used to construct and deconstruct gifs.

### Review
Although this package is used for advanced image manipulation, it is quite simple to use. I like it because it does precise image processing with simple functions, including the addition of text. I discovered `magick` when I was unable to use another favorite package (`patchwork`) to compile a multi-panel plot. In my case, `patchwork` could not recognize ternary diagrams produced by `ggtern` because the usual ggplot geometry (ie x-y coordinates) had been overwritten and lost. With this package it is easy combine different file types (png, jpg, etc), cropping, resizing, layering, etc. I like that you store images as objects, and then combine them together in a number of differet ways. I also like that you can use pipe syntax to make your code easily readable. 

In many ways, this package allows you to do some of the things you can do in programs like Photoshop in R, but the vignetts and tutorials make it surprisingly simple to use. The main help page is organized extremly well, with **pictures**, so each thing you wish to do (re-size, stack, overlay, annotate, etc) it is simple to find at a glance.

Overall, I think this package is amazing, I highly recommend it, and it can probably do far more than I've used it for!
