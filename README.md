## Code to convert geosoft grids to geotiffs based on info at:

https://help.seequent.com/Oasis-montaj/9.9/en/Content/ss/process_data/grid_data/c/geosoft_grid_file_format.htm plus info that compression is in fact zlib not LZRW1 regardless of what COMP_TYPE says! (Thanks Evren Pakyuz-Charrier).

### Current development of this code has been taken up by Fatiando:    
https://github.com/fatiando/harmonica/blob/main/harmonica/_io/oasis_montaj_grd.py 

### Also available here as command line version, usage python   
Usage: python grd2geotiff.py input_grid_path [string] epsg [int]
   
### Test data
From CPRM Open Access geophysical data server https://geosgb.cprm.gov.br/geosgb/downloads.html
