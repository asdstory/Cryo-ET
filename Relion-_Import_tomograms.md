### This section shows how to import a data set whose tomograms have already been aligned using IMOD and the CTF estimated with CTFFind or CtfPlotter.

*Following instructions are from: https://relion.readthedocs.io/_/downloads/en/latest/pdf/*
```sh
# tomograms_descr.star

data_global

loop_
_rlnTomoName
_rlnTomoTiltSeriesName
_rlnTomoImportCtfFindFile
_rlnTomoImportImodDir
_rlnTomoImportFractionalDose

 TS_01   tomograms/TS_01/01.mrc   tomograms/TS_01/01_output.txt   tomograms/TS_01   3.0
 TS_03   tomograms/TS_03/03.mrc   tomograms/TS_03/03_output.txt   tomograms/TS_03   3.0
 TS_43   tomograms/TS_43/43.mrc   tomograms/TS_43/43_output.txt   tomograms/TS_43   3.1
 TS_45   tomograms/TS_45/45.mrc   tomograms/TS_45/45_output.txt   tomograms/TS_45   3.1
 TS_54   tomograms/TS_54/54.mrc   tomograms/TS_54/54_output.txt   tomograms/TS_54   3.0
 ```
