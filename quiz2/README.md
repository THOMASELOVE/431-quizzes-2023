# Quiz 2 Materials

This page will eventually have links to all materials for Quiz 2.

## Instructions

By 5 PM on Thursday 2023-11-30, the complete instructions, including all questions, will be **posted here**.

## R Packages and `Love-boost.R` script used in the Quiz

This doesn't mean I actually used all of these packages. It means that this list includes everything I did use in creating the Quiz and its answers.

```{r}
#| message: false

library(boot); library(broom); library(car); library(corrr)
library(Epi); library(googlesheets4); library(GGally); library(ggdist)
library(ggrepel); library(glue); library(gt); library(gtExtras)
library(haven); library(Hmisc); library(janitor); library(kableExtra)
library(knitr); library(MASS); library(mice); library(mitml)
library(mosaic); library(naniar); library(patchwork); library(pwr)
library(readxl); library(simputation); library(vcd); library(xfun)
library(tidyverse)

source("https://raw.githubusercontent.com/THOMASELOVE/431-data/main/data-and-code/Love-boost.R")

theme_set(theme_bw())

opts_chunk$set(comment = NA)
options(tidyverse.quiet = TRUE)
options(dplyr.summarise.inform = FALSE)
```

## Data

In our Shared Drive, in the Quiz 2 Materials folder (and the data subfolder within it), I **will provide** data sets that are mentioned in the Quiz and which may be helpful to you, specifically:

- list to come.

## Google Form Answer Sheet

All of your answers should be placed in the Google Form Answer Sheet located at <https://bit.ly/431-2023-quiz2-form>. The form will open for your responses **by 5 PM on Thursday 2023-11-30**.

- All of your answers must be submitted through the Google Form by noon on Tuesday 2023-12-05, without exception.
- The form will close at 1 PM that Tuesday (to allow you up to one hour's leeway), and no extensions will be made available, so do not wait until the last minute on Tuesday to submit your work.
- We will only accept responses through the Google Form.

If you wish to work on some of the quiz and then return later, you can do this by:

1. completing the final question (the affirmation) which asks you to type in your full name, and then
2. submitting the quiz.

You will then receive a link at your CWRU email which will allow you to return to the quiz as often as you like without losing your progress.
  
## Fair materials for me to draw from in Quiz 2

- [Classes](https://github.com/THOMASELOVE/431-classes-2023/tree/main) 1-23, including the Slides and Class READMEs,
- [Course Notes](https://thomaselove.github.io/431-notes/), Chapters 1-32 and 35.
- Spiegelhalter's *Art of Statistics* Chapters 1-12,
- [Labs](https://github.com/THOMASELOVE/431-labs-2023) 1-7,
- our [Minute Papers](https://github.com/THOMASELOVE/431-minute-2023) after classes 3, 5, 9, 11, 13, 15, 18 and 23,
- our [Favorite Movies work](https://github.com/THOMASELOVE/431-classes-2023/tree/main/movies), and
- all of [Project A](https://thomaselove.github.io/431-projectA-2023/) and the required analyses in Studies 1 and 2 of [Project B](https://thomaselove.github.io/431-projectB-2023/)

This does not mean I will actually address all of these things in the Quiz. I definitely will not.
