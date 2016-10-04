
TimeScape is a visualization tool for temporal clonal evolution.

To run TimeScape, type the following commands in R:

install.packages("devtools") # if not already installed  
library(devtools)  
install_bitbucket("MO_BCCRC/timescape")  
library(timescape)  
example(timescape) # to run example

And the following visualization of the acute myeloid leukemia patient from Ding et al., 2012 will appear in your browser (optimized for Chrome):

![](timescape_htmlwidget-2699.png)

TimeScape was developed at the Shah Lab for Computational Cancer Biology at the BC Cancer Research Centre.

References:
Ding, Li, et al. "Clonal evolution in relapsed acute myeloid leukaemia revealed by whole-genome sequencing." Nature 481.7382 (2012): 506-510.
