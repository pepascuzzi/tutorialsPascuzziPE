# tutorialsPascuzziPE

These learnR tutorials were written to teach R and tidyverse to students not majoring in a data science domain, predominately the life sciences.  They are a work in progress.  You will need to install the packages **devtools** and **learnr** to run the tutorials.

There are currently four tutorials:

+ "T01_GettingStarted"
+ "T02_DataTypes"
+ "T03_UsingVectors"
+ "T04_Tibbles"
+ "T05_IntroT0Ggplot2"
+ "T06_DataWrangling01"

You run a tutorial using the `run_tutorial` function in the **learnr** package.

# Example

```
install.packages(c("learnr", "devtools"))
devtools::install_github("https://github.com/pepascuzzi/tutorialsPascuzziPE.git")
library(learnr)
run_tutorial(name="T01_GettingStarted", package="tutorialsPascuzziPE")
```
