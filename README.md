# get_receptor_data

```
{
  "user": "rbianconi",
  "repository": "https://www.example.com/data",
  "_comment_src_folder": "This is the local folder where src files are stored",
  "src_folder": "./src",
  "_comment_destination_folder": "This is the local folder where model data will be stored",  
  "destination_folder": "./recfiles",
  "datasets": {
    "0256" : {
      "_comment_r": "Specify a list of variables of interest",
      "001": ["01","02","05"]
    }
  },
  models: [10701,10705],
  "_comment_stations": "Specify a list of stations (Use LCODE), or leave empty for all stations",
  "stations": [],
  "criteria": {
    "_comment_landuse1": "Specify one or more among RURAL,URBAN... or leave empty for any landuse1",
    "landuse1": [],
    "_comment_landuse2": "Specify one or more among AGRICULTURAL... or leave empty for any landuse2",
    "landuse2": [],
    "_comment_network": "Specify one or more among networks or leave empty for any network",
    "network": [],
    "_comment_elevation_range": "Specify mionimum and maximum terrain elevation or leave empty for any elevation",
    "elevation_range": [],
    "_comment_latitude_range": "Specify mionimum and maximum latitude or leave empty for any latitude",    
    "latitude_range": [],
    "_comment_longitude_range": "Specify mionimum and maximum longitude or leave empty for any longitude",        
    "longitude_range": [],
    "_comment_valid_theshold_pct": "Specify minimum percentage of valid data.",    
    "valid_threshold_pct: 0
   }
}

```
