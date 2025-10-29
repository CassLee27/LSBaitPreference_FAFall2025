# LSBaitPreference_FAFall2025
Data and code for statistical analyses and data visualization for research on rodent bait preference at Living Springs. Research conducted as part of the Frontiers Abroad Earth Systems program.

Data files 
* RatData.tsv
  * Codified rat trail camera video data
* MouseData.tsv
  * Codified mouse trail camera video data
* full_data_trapnz.csv
  * Trap.NZ records

Code files
* Rat_LS_FA.Rmd
  * EDA, statistical analysis, data visualization for rat trail camera data
* Mouse_LS_FA.Rmd
  * EDA, statistical analysis, data visualization for mouse trail camera
* TrapNZ_LS_FA.Rmd
  * Statistical analysis, data visualization for Trap.NZ records
* Resetting_EDA_LS_FA.Rmd
  * Additional exploratory data analysis comparing self-resetting and non-self-resetting traps (ex. average servicing interval, sample size)

Possible problem: changing the graph font may not work for all users, commenting out the command that includes: "+ theme(text = [...] )" in the code for the graphs should resolve this issue.

This code was hacked together by someone with limited R experience - if any of it is too incomprehensible, feel free to reach out by mentioning me @CassLee27 in a discussion post for the repository!
