Plotsettings.h contains two lists, one exclusive and one inclusive, of theoretical uncertainties, from 0-7 bins.

Plotsettings.cc: From lines 613-656, the code checks to see the jet binning associated with the variable. Variables associated with one jet bin (i.e. inclusive one jet) have the appropriate scale factor applied to the entire histogram. Variables associated with the full inclusive or exclusive jet bins plot have the appropriate scale factors applied bin by bin. Line 439 was modified to add the aMC@NLO Monte Carlo to the Stat. + Syst. legend string.
