# GAPs10m

## Overview

GAPs10m is a task-specific segmentation package derived from the German Asphalt Pavement Distress dataset (GAPs 10m) with pixel-level labels.

- Task: segmentation
- Images: 20
- Annotations: 345
- Classes in local package stats: 18 (applied_patch, cobblestone, crack, curb, drill_hole, expansion_joint, inlaid_patch, joint, object_fixed, object_mobile, open_joint, pothole, road_marking, road_verge, scratch, sealed_crack, surface_water_drain, vegetation)
- Annotation format: grayscale PNG masks (class-coded)

This local copy contains 20 paired image-mask samples from the GAPs 10m segmentation release.

## Source Dataset

- Name: German Asphalt Pavement Distress Dataset - GAPs 10m
- Source URL: https://www.tu-ilmenau.de/neurob/data-sets-code/german-asphalt-pavement-distress-dataset-gaps
- Source paper: https://ieeexplore.ieee.org/document/9551591

## Access Requirement

The source website states the dataset is not fully open download. Access requires written permission and login credentials for academic use.

## Acquisition Process (as described on source website)

1. Install downloader package: `pip install gaps-dataset`
2. Send completed request form to provider email to receive login:
   - Form: https://www.tu-ilmenau.de/fileadmin/Bereiche/IA/neurob/Datasets/Request-Gaps3.pdf
   - Email: nikr-datasets-request@tu-ilmenau.de
3. Download GAPs10m segmentation with provider-issued login:
   - `gaps.download(login='...', output_dir='...', version='10m', patchsize='segmentation', issue='ASFaLT')`

## Camera Viewpoint

- Top-down road-surface viewpoint (vehicle-mounted surface camera setup)

## Package Contents

- METADATA.json
- stats/
- visualizations/
- ABSTRACT.md
- SUMMARY.md
- CITATION.bib
- CITATION.md
- DOWNLOAD.md
- LICENSE.md
