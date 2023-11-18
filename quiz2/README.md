# Quiz 2 Materials

## R Packages and `Love-boost.R` script used in the Quiz

```{r}
#| message: false

library(boot); library(broom); library(car); library(corrr)
library(Epi); library(GGally); library(ggdist); library(ggrepel)
library(glue); library(gt); library(gtExtras); library(haven)
library(Hmisc); library(janitor); library(kableExtra); library(knitr)
library(MASS); library(mice); library(mitml); library(mosaic)
library(naniar); library(patchwork); library(pwr); library(readxl)
library(simputation); library(vcd); library(xfun)
library(tidyverse)

source("https://raw.githubusercontent.com/THOMASELOVE/431-data/main/data-and-code/Love-boost.R")

theme_set(theme_bw())

opts_chunk$set(comment = NA)
options(tidyverse.quiet = TRUE)
options(dplyr.summarise.inform = FALSE)
```
