# mghUuid - Device query, with some MIG-specific goodies

## Description

This sample enumerates the properties of the CUDA devices present in the system,
including MIG devices and their UUIDs. This was forked from the deviceQuery
sample.

## Supported OSes

Linux

## Supported CPU Architecture

x86_64

## CUDA APIs involved

### NVML

### [CUDA Runtime API](http://docs.nvidia.com/cuda/cuda-runtime-api/index.html)
cudaSetDevice, cudaGetDeviceCount, cudaGetDeviceProperties, cudaDriverGetVersion, cudaRuntimeGetVersion

## Prerequisites

Download and install the [CUDA Toolkit 11.0](https://developer.nvidia.com/cuda-downloads) for your corresponding platform. Make sure to download the NVML dev library as well.

## Build and Run

### Linux
```
$ make
```

