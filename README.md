# favorite_SAS_macros

This (unfortunately poorly updated) repository contains some random personal SAS macros. These were often coded without intention to share, but I'm happy to provide more information and walk you through it should anyone find them useful and want to replicate them. 

**Column_Names** selects all of the column names from a dataset into a list

**Formatting** just sets a format for 0->0.1, 0.1-> 0.2, etc. and 0 -> 0.05, 0.05 -> 0.1, etc. 

**Testing_Variables_In_Logistic** takes a variable list (needs to be identified in advance), feeds it into a stepwise logistic regression, then runs the logistic regression to generate results. The results are then plotted on a gains chart. 

**Generate_Gains_Chart** Makes a Gains chart - it should be noted this is different than an ROC curve. This looks at the total number of the increase in outcome variable over the increase in population. 
