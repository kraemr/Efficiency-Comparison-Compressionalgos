# Efficiency-Comparison-Compressionalgos
Compares some of the most used compression algorithms to determine which of them are worth using








```
lzbench 1.8 (64-bit Linux)  AMD Ryzen 7 5700G with Radeon Graphics         
Assembled by P.Skibinski

Compressor name         Compress. Decompress. Compr. size  Ratio Filename
memcpy                  44664 MB/s 46425 MB/s    10192446 100.00 ../uncompressed/dickens
zstd 1.5.2 -1             377 MB/s  1617 MB/s     4261734  41.81 ../uncompressed/dickens
zstd 1.5.2 -2             243 MB/s  1390 MB/s     3864999  37.92 ../uncompressed/dickens
zstd 1.5.2 -4             191 MB/s  1333 MB/s     3587632  35.20 ../uncompressed/dickens
zstd 1.5.2 -8            53.0 MB/s  1502 MB/s     3301774  32.39 ../uncompressed/dickens
lz4 1.9.3                 530 MB/s  4409 MB/s     6428742  63.07 ../uncompressed/dickens
bzip2 1.0.8 -1           20.1 MB/s  50.5 MB/s     3302765  32.40 ../uncompressed/dickens
bzip2 1.0.8 -2           20.6 MB/s  45.7 MB/s     3112033  30.53 ../uncompressed/dickens
bzip2 1.0.8 -4           20.2 MB/s  42.4 MB/s     2949415  28.94 ../uncompressed/dickens
bzip2 1.0.8 -8           19.3 MB/s  41.1 MB/s     2821149  27.68 ../uncompressed/dickens
brotli 1.0.9 -1           205 MB/s   417 MB/s     4042051  39.66 ../uncompressed/dickens
brotli 1.0.9 -2           134 MB/s   479 MB/s     3899491  38.26 ../uncompressed/dickens
brotli 1.0.9 -4          56.9 MB/s   610 MB/s     3437599  33.73 ../uncompressed/dickens
brotli 1.0.9 -8          12.5 MB/s   636 MB/s     3154565  30.95 ../uncompressed/dickens
xz 5.2.5 -1              19.0 MB/s  91.4 MB/s     3661477  35.92 ../uncompressed/dickens
xz 5.2.5 -2              9.49 MB/s  99.8 MB/s     3473179  34.08 ../uncompressed/dickens
xz 5.2.5 -4              3.00 MB/s   126 MB/s     2925618  28.70 ../uncompressed/dickens
xz 5.2.5 -8              2.35 MB/s   129 MB/s     2830116  27.77 ../uncompressed/dickens
zlib 1.2.11 -1           92.6 MB/s   394 MB/s     4585618  44.99 ../uncompressed/dickens
zlib 1.2.11 -2           80.9 MB/s   410 MB/s     4389480  43.07 ../uncompressed/dickens
zlib 1.2.11 -4           57.9 MB/s   409 MB/s     4095027  40.18 ../uncompressed/dickens
zlib 1.2.11 -8           15.0 MB/s   410 MB/s     3854735  37.82 ../uncompressed/dickens
zstd 1.5.2 -1             481 MB/s  1349 MB/s     3606036  58.61 ../uncompressed/ooffice
zstd 1.5.2 -2             351 MB/s  1296 MB/s     3321249  53.98 ../uncompressed/ooffice
zstd 1.5.2 -4             210 MB/s  1222 MB/s     3069548  49.89 ../uncompressed/ooffice
zstd 1.5.2 -8            73.6 MB/s  1254 MB/s     2892647  47.02 ../uncompressed/ooffice
lz4 1.9.3                 729 MB/s  4421 MB/s     4338918  70.53 ../uncompressed/ooffice
bzip2 1.0.8 -1           19.2 MB/s  43.6 MB/s     3003039  48.81 ../uncompressed/ooffice
bzip2 1.0.8 -2           20.4 MB/s  41.1 MB/s     2943226  47.84 ../uncompressed/ooffice
bzip2 1.0.8 -4           20.5 MB/s  39.1 MB/s     2887156  46.93 ../uncompressed/ooffice
bzip2 1.0.8 -8           20.1 MB/s  37.9 MB/s     2855019  46.41 ../uncompressed/ooffice
brotli 1.0.9 -1           240 MB/s   298 MB/s     3476006  56.50 ../uncompressed/ooffice
brotli 1.0.9 -2           137 MB/s   318 MB/s     3168302  51.50 ../uncompressed/ooffice
brotli 1.0.9 -4          61.6 MB/s   338 MB/s     3188512  51.83 ../uncompressed/ooffice
brotli 1.0.9 -8          10.0 MB/s   364 MB/s     2771914  45.06 ../uncompressed/ooffice
xz 5.2.5 -1              17.0 MB/s  62.8 MB/s     2668207  43.37 ../uncompressed/ooffice
xz 5.2.5 -2              10.4 MB/s  64.5 MB/s     2634629  42.82 ../uncompressed/ooffice
xz 5.2.5 -4              4.58 MB/s  66.5 MB/s     2448659  39.80 ../uncompressed/ooffice
xz 5.2.5 -8              4.03 MB/s  65.8 MB/s     2426397  39.44 ../uncompressed/ooffice
zlib 1.2.11 -1           67.4 MB/s   280 MB/s     3290532  53.49 ../uncompressed/ooffice
zlib 1.2.11 -2           62.6 MB/s   284 MB/s     3238288  52.64 ../uncompressed/ooffice
zlib 1.2.11 -4           48.7 MB/s   292 MB/s     3158018  51.33 ../uncompressed/ooffice
zlib 1.2.11 -8           16.4 MB/s   303 MB/s     3093032  50.28 ../uncompressed/ooffice
```
