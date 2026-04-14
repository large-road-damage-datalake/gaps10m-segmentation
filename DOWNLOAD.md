# Download

## Official Source

- Dataset page: https://www.tu-ilmenau.de/neurob/data-sets-code/german-asphalt-pavement-distress-dataset-gaps

## Permission Requirement

The source provider states access is permission-based (academic use). You need a completed request form and provider-issued login.

## Acquisition Steps

1. Install package:
   - `pip install gaps-dataset`
2. Submit request form:
   - Form: https://www.tu-ilmenau.de/fileadmin/Bereiche/IA/neurob/Datasets/Request-Gaps3.pdf
   - Email: nikr-datasets-request@tu-ilmenau.de
3. Download segmentation set once login is granted:
   - `gaps.download(login='...', output_dir='...', version='10m', patchsize='segmentation', issue='ASFaLT')`

## Package Repository

- Task package: https://github.com/large-road-damage-datalake/gaps10m-segmentation
