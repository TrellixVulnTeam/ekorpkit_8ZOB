# NCBI-disease
 
<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=../../../../ekorpkit/resources/datasets/t5/NCBI-disease.yaml) -->
<!-- The below code snippet is automatically added from ../../../../ekorpkit/resources/datasets/t5/NCBI-disease.yaml -->
```yaml
name: NCBI-disease
domain: biomed
task: ner
lang: en
num_examples: 7287
size_in_bytes: 1039641
size_in_human_bytes: 1015.27 KiB
data_files_modified: '2022-02-26 03:01:45'
info_updated: '2022-02-26 03:06:01'
data_files:
  train: NCBI-disease-train.csv
  dev: NCBI-disease-dev.csv
  test: NCBI-disease-test.csv
column_info:
  columns:
    id: id
    text: input_text
  data:
    id: int
    prefix: str
    input_text: str
    target_text: str
```
<!-- MARKDOWN-AUTO-DOCS:END -->
