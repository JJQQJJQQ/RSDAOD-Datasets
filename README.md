# SASCAN Datasets

This repository contains the cross-domain object detection datasets used in the **SASCAN** project for remote sensing imagery.

## Download

All dataset files can be obtained via Baidu Netdisk:

- **Link**: https://pan.baidu.com/s/1MI_0pAE-8CyT3jsQbt20dw
- **Extraction Code**: `k7p6`

## Supported Datasets

This project supports multiple cross-domain object detection scenarios, including:

- NWPU_VHR_10 → DIOR
- HRRSD → DIOR
- NWPU_VHR_10 → VEDAI
- NWPU_VHR_10 → VEDAIIR
- HRRSD → SSDD

All datasets are constructed from publicly available remote sensing sources.

## Directory Organization

The dataset root directory can be specified via the environment variable `DETECTRON2_DATASETS`, with the default path being `/datasets`. Please organize as follows:

```
datasets/
├── DIOR/
│   └── coco/
├── HRRSD/
│   └── coco_10c/
├── NWPU_VHR_10/
│   └── coco/
├── VEDAI/
│   └── coco/
└── SSDD/
    └── coco/
```

## Notes

- The source code of the SASCAN project is currently kept private.
- For dataset annotation formats and preprocessing details, please refer to the official SASCAN repository (private) or contact the authors.

## License

These datasets are derived from publicly available remote sensing datasets. Please refer to the original licenses of each dataset for usage terms.
