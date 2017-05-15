# Datasets for bar-frequencies paper using S4G data

## Main combined-data table

`s4gbars_table.dat` = data for 1322 individual galaxies in Parent Disk Sample.


## Tables of bar presence/absence

These tables list bar presence/absence (coded as 1 or 0) for galaxies in Sample 1
with log stellar mass between 8.5 and 11 along with log stellar mass, weights, and
(for the 2nd and 3rd table) either g-r color or log of gas mass ratio.

(These tables can be regenerated by code in the Python `XXX` notebook.)

   * `barpresence_vs_logmstar_for_R_w25_m8.5-11.txt` (563 galaxies)
   
   * `barpresence_vs_logmstar-gmr_for_R_w25.txt` (319 galaxies)
   
   * `barpresence_vs_logmstar-logfgas_for_R_w25.txt` (556 galaxies)


For use with R notebook `s4gbars_R_logistic-regression.ipynb` for weighted logistic regression
analysis.