# Hybrid learning model for spatio-temporal forecasting of PM2.5 using aerosol optical depth

### Directory
The repository is structured on the basis of 3 cities mentioned in the study along with the pollution data used.

> :warning: Please **DO NOT** run the notebooks in your local machine due to non-matching dependencies. Refer to the [workbench_environment.txt](./workbench_environment.txt) for specific package versions.

```
.
├── Bengaluru
│   ├── 001-Explore-MCD19A2-HDF.ipynb
│   ├── 002-Weekly-Resample.ipynb
│   ├── 003-Forecast-PM2.5_ML.ipynb
│   ├── 004-Forecast-PM2.5_Statistical.ipynb
│   ├── 005-Forecast-PM2.5_DL.ipynb
│   ├── 006-Convert-PM2.5-AOD.ipynb
│   ├── 007-Model-Spatial-Relation-Station.ipynb
│   ├── 03A-Forecast-PM2.5_ML-All.ipynb
│   ├── 03B-Forecast-PM2.5_ML-Data.ipynb
│   ├── 03C-Forecast-PM2.5_ML-Data-Paper.ipynb
│   ├── 04A-Forecast-PM2.5_Stat-All.ipynb
│   ├── 04B-Forecast-PM2.5_Stat-Data.ipynb
│   ├── 04C-Forecast-PM2.5_Stat-Data-Paper.ipynb
│   ├── 05A-Forecast-PM2.5_DL-All.ipynb
│   ├── 05B-Forecast-PM2.5_DL-Data.ipynb
│   ├── 05C-Forecast-PM2.5_DL-Data-Paper.ipynb
│   ├── 06A-Model-PM2.5-AOD.ipynb
│   ├── 07A-Convert-PM2.5-AOD-All.ipynb
│   ├── 08A-Model-Spatial-Relation-Station-All.ipynb
│   ├── 08B-Model-Spatial-Relation-Bengaluru-All.ipynb
│   ├── 08C-Model-Spatial-Relation-Bengaluru-All-PM2.5.ipynb
│   ├── 09A-Model-Final.ipynb
│   ├── 09B-Model-Final-Data.ipynb
│   ├── 09D-Model-Final-Data-2.ipynb
│   └── A00-Explore-Bengaluru.ipynb
├── Kolkata
│   ├── ...
├── Mumbai
│   ├── ...
├── Pollution Data
│   ├── city_day.csv
│   ├── city_hour.csv
│   ├── config.ini
│   ├── delhi_stations.pkl
│   ├── delhi_stations_pm25.pkl
│   ├── extract_city_stations.ipynb
│   ├── extract_delhi_pm25_stationwise.ipynb
│   ├── extract_delhi_stations.ipynb
│   ├── extract_india_pm25_stationwise.ipynb
│   ├── extract_india_stations.ipynb
│   ├── extract_station_names.ipynb
│   ├── india_stations-corrected.csv
│   ├── india_stations.csv
│   ├── india_stations.pkl
│   ├── india_stations_pm25.pkl
│   ├── station_day.csv
│   ├── station_hour.csv
│   └── stations.csv
├── README.md
└── tree.txt

4 directories, 95 files

```

### Citation
Please cite this paper if you use the code/data in your research.

```
@article{nath2022hybrid,
    title={Hybrid learning model for spatio-temporal forecasting of PM2.5
    using aerosol optical depth},
    author={Nath, Pritthijit and Roy, Biparnak and Saha, Pratik and Middya, Asif Iqbal and Roy, Sarbani},
    journal={Neural Computing and Applications},
    year={2022},
    month={Aug},
    pages={1-20},  
    issn={1433-3058},
    url={https://link.springer.com/article/10.1007/s00521-022-07616-4},
    doi={10.1007/s00521-022-07616-4}
}
```