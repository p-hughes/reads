# Soil map generator

## How to convert EM and Gamma to a soil property map

Step one: import class

```R
library(phillsfunctions)
```



Step two: import dataset (in either single csv format of fragmented csv format)

```R
generatedataset("path/to/file/dataset1.csv","path/to/file/dataset2.csv")
```
Make sure that dataset1 is of the format:
```
eastings,northings,id,lon,lat,sdfrom,sdto,rest_of_data
```
