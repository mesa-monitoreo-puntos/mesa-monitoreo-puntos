# Mesa de monitoreo por puntos

## Instalación

### Directamente en R
```r
install.packages(c('devtools', 'rodbc', 'sqldf', 'httr', 'gdal', 'libgdal, 'raster', 'geos', 'sp', 'data.table', 'rcpp', 'sf'))
```

### Con Conda
#### Creación del ambiente Conda
```shell
conda update conda
conda create -n mesa-monitoreo-puntos
conda activate mesa-monitoreo-puntos
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install r-base r-essentials r-devtools r-rodbc r-sqldf r-httr gdal libgdal r-raster geos r-sp r-data.table r-rcpp r-sf
```

#### Activación del ambiente Conda
```shell
conda activate mesa-monitoreo-puntos
```
