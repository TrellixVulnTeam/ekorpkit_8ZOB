# BC5CDR-chem
 
<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=../../../../ekorpkit/resources/datasets/t5/BC5CDR-chem.yaml) -->
<!-- The below code snippet is automatically added from ../../../../ekorpkit/resources/datasets/t5/BC5CDR-chem.yaml -->
```yaml
name: BC5CDR-chem
domain: biomed
task: ner
lang: en
num_examples: 13938
size_in_bytes: 2043073
size_in_human_bytes: 1.95 MiB
data_files_modified: '2022-02-26 03:02:43'
info_updated: '2022-02-26 03:06:01'
data_files:
  train: BC5CDR-chem-train.csv
  dev: BC5CDR-chem-dev.csv
  test: BC5CDR-chem-test.csv
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
