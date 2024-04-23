# Non-parametric Regression; all code by Ryan Dekker

These data are from Southern broadcasters in a larger project to see show common "Southern accents" are in local media here in the 2020s. This phonetic data set of 80 speakers tracks the presence of the "PIN-PEN" merger (a feature of a 'Southern accent'). This merger is quantified via Pillai score, where a lower number means more vowel overlap and is thus more "Southern".
 
 The R Markdown file shows how the data were tested for normality both using hte Shapiro-Wilk test and in a visual representation of the skewed data and the theoretical curve of normality. Because the data failed the hypotheses of normality, the data were used in a non-parametric test of bootstrapping (using the "boot" package). This resampling technique found that three indpendent variables among all the demographic information met the 95% confidence interval for significance. 

The histogram of the 80 speakers' Pillai score is uplaoded in this repo. 

