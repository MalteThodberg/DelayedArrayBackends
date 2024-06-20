# DelayedArrayBackends
Overview of implemented DelayedArray backends (most likely incomplete):

## Bioconductor
- matrix / array: [DelayedArray](https://bioconductor.org/packages/release/bioc/html/DelayedArray.html)
- Rle: [DelayedArray](https://bioconductor.org/packages/release/bioc/html/DelayedArray.html)
- HDF5: [HDF5Array](https://bioconductor.org/packages/release/bioc/html/HDF5Array.html)
- TileDb: [TileDBArray](https://bioconductor.org/packages/release/bioc/html/TileDBArray.html)
- VCF: [VCFArray](https://bioconductor.org/packages/release/bioc/html/VCFArray.html)
- DataFrame: [DelayedDataFrame](https://bioconductor.org/packages/release/bioc/html/DelayedDataFrame.html)
- SQL: [SQLDataFrame](https://bioconductor.org/packages/release/bioc/html/SQLDataFrame.html)
- GDS: [GDSArray](https://bioconductor.org/packages/release/bioc/html/GDSArray.html) & [SCArray](https://bioconductor.org/packages/release/bioc/html/SCArray.html)

## Github
- bigmemory: [BigArray](https://github.com/MalteThodberg/BigArray)
- matter: [matterArray](https://github.com/PeteHaitch/matterArray)
- fst: [fstArray](https://github.com/PeteHaitch/fstArray)
- DuckDb / parquet: [delaytional](https://github.com/WEHI-ResearchComputing/delaytional)
- parquet: [parquetDataFrame](https://github.com/LTLA/ParquetDataFrame)

## Other on-disk format without a DelayedArray backend:
- [filematrix](https://cran.r-project.org/web/packages/filematrix/index.html)
- [feather](https://cran.r-project.org/web/packages/feather/index.html)
- [ff](https://cran.r-project.org/web/packages/ff/index.html)
- [zarr](https://bioconductor.org/packages/Rarr/)
- [txt](https://cran.r-project.org/web/packages/LaF/index.html)
