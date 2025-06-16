# data_Vydula_2025_LNPS
Data to support the findings in Vydula et al, 2025
The report is available on arXiV, and accepted for publication in Physical Review C.


The repository consists of two folders:
Maps
  -20deg map used from PDS (obtained from LP GRS and NS) 
  
  -5deg map used from PDS (obtailed from LP GRS and NS)

  The files provide latitude and longitude bounds of each pixel (rows) and corresponding elemental mass fractions (columns). 
  
MCNP results
  -20deg map, latitude independent temperature 
  
  -20deg map, latitude dependent temperature 
  
  -5deg map, latitude dependent temperature
  
  -five compositions used in Wilson 2021, latitude independent temperature
  
MCNP results are reported as current tallys without source flux normalization in 400 energy bins that are equally spaced between 1e-9 to 1e4 MeV (rows). For each pixel of the map, the energy, current tally and the error in tally are reported. For instance [current_0	energy_0	error_0] give the tally result, energy and error in tally for the pixel_0 in the map.

