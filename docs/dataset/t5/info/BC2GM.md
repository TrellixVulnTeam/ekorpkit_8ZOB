# BC2GM
 
<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=../../../../ekorpkit/resources/datasets/t5/BC2GM.yaml) -->
<!-- The below code snippet is automatically added from ../../../../ekorpkit/resources/datasets/t5/BC2GM.yaml -->
```yaml
name: BC2GM
domain: biomed
task: ner
lang: en
num_examples: 20131
size_in_bytes: 3157292
size_in_human_bytes: 3.01 MiB
data_files_modified: '2022-02-26 03:02:14'
info_updated: '2022-02-26 03:06:01'
data_files:
  train: BC2GM-train.csv
  dev: BC2GM-dev.csv
  test: BC2GM-test.csv
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
