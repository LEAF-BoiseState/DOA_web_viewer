```
/opt/shiny-server/bwc/climate-viewer/
----| app.R
    | busyIndicator.R
    | buttonIndicator.R
    | www/ # <- Static webpage material (images, etc.)
    | data/ # <- Data supporting the climate viewer
    ----| MON_Anomalies_d02.nc # <- Anomalies for each month (MON) for entire d02 WRF domain
        | MON_AVA_Anomalies_d02.nc # <- Anomalies for each month (MON) for the AVA region
        | AVA_WYNNNN_yearly_stats_d02.nc # <- yearly statistics for water year NNNN for AVA region
        | WYNNNN_yearly_stats_d02.nc # <- yearly statistics for water year NNNN for entire d02 WRF domain
        | clay_d02 # < soil grids, percent clay (right now in arcgis format)
        | sand_d02 # < soil grids, percent sand (right now in arcgis format)
        | silt_d02 # < soil grids, persent silt (right now in arcgis format)
        | AVA_30YR_df_all_vars.csv # <- CSV-format dataframe of statistics at all Lat/Long points of the AVA region
        | AVA_30YR_NoLeap917.csv # <- AVA-wide statistics for each day (no leap years)
        | d01_30YR_NoLeap917.csv # <- d01-wide statistics for each day (no leap years)
        | d02_30YR_NoLeap917.csv # <- d02-wide statistics for each day (no leap years)
        | SS_30YR_NoLeap917.csv  # <- Sunny Slope point statistics for each day (no leap years)
```
