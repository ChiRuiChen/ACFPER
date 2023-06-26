# ACFPER
Official repository of the Accelerating CNNs on FPGAs for Particle Energy Reconstruction paper.

## Intro
The work presented in this paper is based on the release version 0.5.1 of hls4ml.

## Links
### DeepCalo
- [Deepcalo library Official](https://gitlab.com/ffaye/deepcalo)
- [Deepcalo library integrated with qkeras](https://gitlab.com/kugelblitz.ee05/deepcalo-with-hls-4-ml)

### hls4ml
- [Latency Optimized](https://github.com/YanLunHuang/hls4ml/tree/Array_Single_AutoConvert_22_9_16)

Includes a flexible switch mechanism between single-stream and array-of-streams, this branch only supports image-only models currently.

- [Resource Optimized](https://github.com/ChiRuiChen/hls4ml/tree/Single-stream)

A resource-efficient all-single-stream implementation, which can support the full model.

### FPGA implementation
- [Image-only model](https://github.com/YanLunHuang/alveo_u50_image_only_model/tree/2023_1_15_five_set_array)

- [Full model](https://github.com/YanLunHuang/alveo_u50_full_model/tree/2023_2_3_five_set_array)

## Other resources:
- [hls4ml tutorial](https://github.com/fastmachinelearning/hls4ml-tutorial )

- [QKERAS library (includes AUTOQKERAS and QTOOLS)](https://github.com/google/qkeras.)
