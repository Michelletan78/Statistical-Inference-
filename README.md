# Statistical-Inference-
inference for numerical data 
Getting Started
Load packages
Let's load the necessary packages for this week's lab:

library(statsr)
library(dplyr)
library(ggplot2)
As usual, the data set and analysis functions will be provided by the statsr package and we will be using dplyr and ggplot2 for manipulating and visualizing the data.

The data
In 2004, the state of North Carolina released a large data set containing information on births recorded in this state. These data contain information on both the expectant mothers and their children. We will be working with a random sample of the complete data set. For those of you who took the Inferential Statistics course as part of the Statistics with R specialization should recognize this as the same data set used in the Inference for numerical data lab where we used frequentist inference methods to explore these data.

You can load the nc data set into our workspace using the data function once the statsr package is loaded.

data(nc)
This data set consists of 1000 observations on 13 different variables, some categorical and some numerical. The definition of each variable is as follows:

variable	description
fage	father's age in years.
mage	mother's age in years.
mature	maturity status of mother.
weeks	length of pregnancy in weeks.
premie	whether the birth was classified as premature (premie) or full-term.
visits	number of hospital visits during pregnancy.
marital	whether mother is married or not married at birth.
gained	weight gained by mother during pregnancy in pounds.
weight	weight of the baby at birth in pounds.
lowbirthweight	whether baby was classified as low birthweight (low) or not (not low).
gender	gender of the baby, female or male.
habit	status of the mother as a nonsmoker or a smoker.
whitemom	whether mom is white or not white.

