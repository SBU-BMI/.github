# Biomedical Informatics, Stony Brook University

Open-source tools for computational pathology: whole slide image (WSI) analysis, deep learning for histopathology, and the QuIP platform for storing, viewing, and sharing results.

Website: [bmi.stonybrookmedicine.edu](http://bmi.stonybrookmedicine.edu)

## Start here

| Repo | What it is |
|---|---|
| [wsinfer](https://github.com/SBU-BMI/wsinfer) | Patch-based classification pipeline for whole slide images. Pretrained models in [wsinfer-zoo](https://github.com/SBU-BMI/wsinfer-zoo). |
| [champkit](https://github.com/SBU-BMI/champkit) | Benchmarking toolkit for patch-based histopathology image classification. |
| [SpinPath](https://github.com/SBU-BMI/SpinPath) | CLI for specimen-level inference on whole slide images. |
| [quip_distro](https://github.com/SBU-BMI/quip_distro) | Docker Compose distribution of the QuIP platform: caMicroscope viewer, PathDB, and analysis services. |
| [PathDB](https://github.com/SBU-BMI/PathDB) | Image and annotation database behind QuIP. |

## Analysis models

| Repo | What it is |
|---|---|
| [quip_cnn_segmentation](https://github.com/SBU-BMI/quip_cnn_segmentation) | CNN nucleus segmentation. |
| [quip_cancer_segmentation](https://github.com/SBU-BMI/quip_cancer_segmentation) | Tumor region segmentation. |
| [quip_classification](https://github.com/SBU-BMI/quip_classification) | Patch classification models. |
| [u24_lymphocyte](https://github.com/SBU-BMI/u24_lymphocyte) | Tumor-infiltrating lymphocyte (TIL) detection. |
| [quip_paad_cancer_detection](https://github.com/SBU-BMI/quip_paad_cancer_detection), [quip_prad_cancer_detection](https://github.com/SBU-BMI/quip_prad_cancer_detection), [quip_lung_cancer_detection](https://github.com/SBU-BMI/quip_lung_cancer_detection) | Cancer-type-specific detection models. |
| [histopathology_analysis](https://github.com/SBU-BMI/histopathology_analysis) | Deep learning methods for histopathology image analysis. |
| [deep_survival_analysis](https://github.com/SBU-BMI/deep_survival_analysis), [tumor-til-survival-analysis](https://github.com/SBU-BMI/tumor-til-survival-analysis) | Survival analysis from image features. |

## QuIP utilities

| Repo | What it is |
|---|---|
| [cancer-data-bridge](https://github.com/SBU-BMI/cancer-data-bridge) | REST API bridging caMicroscope, 3D Slicer, and MongoDB. |
| [findapi](https://github.com/SBU-BMI/findapi) | Minimal REST interface to MongoDB collections. |
| [SegmentationLoader](https://github.com/SBU-BMI/SegmentationLoader) | Load WSI segmentations into MongoDB. |
| [featuremap_util](https://github.com/SBU-BMI/featuremap_util) | Convert prediction outputs into PathDB featuremaps. |
| [manifest_util](https://github.com/SBU-BMI/manifest_util) | Generate upload manifests for PathDB. |
| [quip_reports](https://github.com/SBU-BMI/quip_reports) | Export image and annotation inventory reports. |
| [quip_converter](https://github.com/SBU-BMI/quip_converter) | Convert vendor slide formats to tiled multiresolution TIFF. |

## Other

| Repo | What it is |
|---|---|
| [SlicerPathology](https://github.com/SBU-BMI/SlicerPathology) | 3D Slicer extension for pathology segmentation. |
| [nscale](https://github.com/SBU-BMI/nscale) | High-performance image analysis libraries (C++, MPI). |
| [region-templates](https://github.com/SBU-BMI/region-templates) | Region Templates runtime for large-scale image analysis. |
| [MappingOHDSI2HDF5](https://github.com/SBU-BMI/MappingOHDSI2HDF5) | JSON mappings from OHDSI tables to HDF5. |

## Funding

This work is supported by NCI U24 and related awards. See individual repositories for grant acknowledgements.

## License

Most repositories are released under the BSD 3-Clause License. Check each repository's `LICENSE` file.

<br>
