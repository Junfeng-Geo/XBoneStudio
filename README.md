# XBone Studio

### An integrated CT/MR research workstation

**Visualize · Edit · Reconstruct · Register**

[中文介绍](README.zh-CN.md) · [Academic homepage](https://junfeng-geo.github.io/)

XBone Studio is a Windows-based workstation for research and teaching, bringing together CT/MR visualization, segmentation editing, 3D reconstruction, and registration in a single interactive workspace. Its development focuses on orthopedic imaging workflows, with current AI integrations oriented toward spine-related tasks.

> **Project showcase.** This repository presents the software and its capabilities. Source code, installers, model weights, and patient data are not publicly distributed here.

## Core capabilities

- **Explore CT and MR volumes:** NIfTI/DICOM import, linked axial/coronal/sagittal views, and label overlays.
- **Edit segmentation masks:** tri-planar painting and erasing, physical-radius controls, undo/redo, and local live surface previews.
- **Work in 3D:** surface reconstruction, region marking, and CT/MRI grayscale inspection inside selected objects.
- **Review alignment:** CT/MR registration and fused viewing, three-point correspondence registration, and ICP surface registration with alignment statistics.
- **Export research outputs:** surface meshes in STL, PLY, and VTP formats.

## A connected research workflow

1. Load and inspect imaging volumes in linked views.
2. Review and refine segmentation labels.
3. Generate and inspect 3D surfaces and selected regions.
4. Align objects and review registration results.
5. Export the resulting geometry for downstream research.

## Development status

XBone Studio is under active development and internal evaluation. Feature descriptions reflect the current research implementation; they are not a claim of clinical performance or validation.

There is no public installer or source release at this stage. The current research build depends on separately configured runtime environments and models. Third-party components and model weights are subject to their respective licenses.

## Intended use

**For research and teaching only. Not intended for clinical diagnosis, treatment, or surgical navigation.**

Patient images, videos, annotations, and datasets are not included. This showcase does not provide a license to the underlying software or third-party models.

## Contact

**Junfeng Jiang · Hohai University**

For research inquiries: [jiangjf@hhu.edu.cn](mailto:jiangjf@hhu.edu.cn)

[Academic homepage](https://junfeng-geo.github.io/) · [GitHub](https://github.com/Junfeng-Geo)
