# spcm_simple.F90

Simplified SI scheme of ARPEGE/IFS.

# Building

This test case requires :

- https://github.com/pmarguinaud/fiat/tree/pginvtx+mplacc
- https://github.com/ecmwf-ifs/ectrans

Building for NVIDIA/PGI (edit Makefile.nvhpc first) :

```

$ make ARCH=nvhpc

```

![](./images/SPCM_SIMPLE.svg)

# Temperature correction T149L105

![](./images/snapshot_0004.png)
