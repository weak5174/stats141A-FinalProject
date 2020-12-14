1) Most of the info in the Markdown file you alrady know how to do but I think the dplyr stuff at the beginning might be useful for dataframe/tibble manipulations for these data.

2) THe end of "Section 4" the following variables (and code) to select the best things to try in stepwise selection-- for either fabs (what I was predicting in the study) OR PM2.5.    

"— Rationale for Stepwise selection —

- To my knowledge, the literature doesn’t indicate any more chemical species that should influence fAbs. -Thus, stepwise selection is appropriate by considering all…
-  Trace elements ( Al, Si, etc.)
-  Non-proxy compounds, e.g., NO3 (nitrate) but not ammNO3 ammonium nitrate as ammonium was not directly measured. Specifically, all nitrate in the sample was ASSUMED to belong to ammonium nitrate. This is not necessarily a great approximation (in general) as sodium nitrate is also contained in aerosols. SOIL and SeaSalt are also excluded.
- Exclude OC and EC fractions (e.g., EC1, OC2, etc.). These are simply used for QC purposes in the IMPROVE network as OC=OC1+OC2+OC3+OC4+OP and EC=EC1+EC2+EC3-OP"

3) THere's also some useful dplyr code at the beginning of Part 5 to remove these variables from stepAIC.


