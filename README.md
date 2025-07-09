# RTS5921_SVD
The SVD file for RTS5921

## Generate Header File
```shell
.\SVDConv.exe .\RTS5921.svd --generate=header --fields=struct --fields=macro -o .\
```

## Generate SFR & SFD
```shell
.\SVDConv.exe .\RTS5921.svd --generate=sfr -o .\
```