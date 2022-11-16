## Code to convert geosoft grids to geotiffs based on info at:

https://help.seequent.com/Oasis-montaj/9.9/en/Content/ss/process_data/grid_data/c/geosoft_grid_file_format.htm plus info that compression is in fact zlib not LZRW1 regardless of what COMP_TYPE says! (Thanks Evren Pakyuz-Charrier).

## Future development of this code has been taken up by Fatiando starting with: https://github.com/fatiando/harmonica/pull/348#issuecomment-1315965084    

Doesn't handle everything yet:      
- Should check data type in ES & SF and handle data types accordingly
- Could write tif->grd as well?
- Could parse XML if present for CRS info
- Could parse .gi file for CRS and other info if I had format...
   
Test data from CPRM Open Access geophysical data server https://geosgb.cprm.gov.br/geosgb/downloads.html
