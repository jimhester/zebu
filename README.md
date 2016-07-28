# zebu

## Description

The `zebu` R package implements different tools related to local association measures in three main functions. It replaces the previous web application written using `shiny`.

- `lassie` estimates local (and global) association measures: Ducher's Z, pointwise mutual information and normalized pointwise mutual information.

- `permtest` accesses the significance of local (and global) association values using  p-values estimated by permutations.

- `subgroups` identifies if the association between variables is dependent on the value of another variable.

## Installation

Install [R](https://www.r-project.org/) and [RStudio](https://www.rstudio.com/).

Get the development version from Github:

```R
# install.packages("devtools")
devtools::install_github("olivmrtn/zebu")
```

## Usage and Theory

Please read the R vignette located in inst/doc/ by typing `vignette(“zebu")` in the R console.

## Contact

* Olivier M. F. Martin, Pharm.D.  
[olivmrtn@gmail.com](mailto:olivmrtn@gmail.com)

* Michel Ducher, Pharm.D., Ph.D  
[michel.ducher@chu-lyon.fr](mailto:michel.ducher@chu-lyon.fr)

## License

Lassie 0.1
Copyright (C) 2016

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

The GNU General Public License is available at [http://www.gnu.org/licenses/]()

The source code can be found at [https://github.com/olivmrtn/zebu]()
