# RSDAOD Datasets

This repository contains the cross-domain object detection datasets used in the **RSDAOD** project for remote sensing imagery.

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
│   └── coco_ship/
├── NWPU_VHR_10/
│   └── coco/
├── VEDAI/
│   └── coco/
└── SSDD/
    └── coco/
```

## License

These datasets are derived from publicly available remote sensing datasets. Please refer to the original licenses of each dataset for usage terms.

## Acknowledgements
We would like to express our gratitude to all researchers who made the benchmark datasets publicly available for this study. Specifically, we thank Li et al. for the DIOR dataset, Cheng et al. for the NWPU VHR-10 dataset, Razakarivony and Jurie for the VEDAI dataset, Y. Zhang et al. for the HRRSD dataset, and J. Li et al. for the SSDD dataset. These high-quality datasets are of great value for validating the proposed method and promoting the research progress of cross-domain remote sensing object detection.

