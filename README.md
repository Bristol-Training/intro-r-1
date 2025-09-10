# Beginning R

This course is written with quarto.

Course dependencies are managed
using `renv`. Dependencies can
be found in the "imports" section
of the `DESCRIPTION` file.

To edit the code, open Rstudio, if you do not have `renv` installed, install it using:

`install.packages("renv")`

Then navigate to the project directory and restore the environment
in the console using:

```r
renv::restore()
```

You will then be able to preview the 
course using the command:

```r
quarto::quarto_preview()
```

This course is deployed automatically when you push changes to GitHub.

Jean Golding Institute © CC-BY 4.0