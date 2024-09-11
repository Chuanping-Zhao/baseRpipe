# baseRpipe

`baseRpipe` is an R package that enhances the usability of the base R pipe operator `|>`. It provides an RStudio add-in that allows users to insert the pipe operator into their scripts via a keyboard shortcut. This functionality is designed to streamline coding workflows in RStudio by simplifying the insertion of the pipe, thus enhancing coding efficiency and readability.

## Installation

You can install the latest development version of the `baseRpipe` package from GitHub. To install this package, you need to first install the `devtools` package if it's not already installed and then use it to install `baseRpipe` from GitHub.

```R
# Install the devtools package if you haven't already
if (!requireNamespace("devtools", quietly = TRUE))
  install.packages("devtools")

# Install baseRpipe from GitHub
devtools::install_github("Chuanping-Zhao/baseRpipe")
```

# Features
The baseRpipe package provides the following features:

Shortcut Plugin: Allows users to quickly insert the R pipe operator |> by pressing Ctrl+M (or another custom shortcut).

# Background
This package was inspired by other tools and packages, particularly the pipe function in the `do` package, and has been expanded and improved upon that basis.



