# JNLPBA
 
<!-- MARKDOWN-AUTO-DOCS:START (CODE:src=../../../../ekorpkit/resources/datasets/t5/JNLPBA.yaml) -->
<!-- The below code snippet is automatically added from ../../../../ekorpkit/resources/datasets/t5/JNLPBA.yaml -->
```yaml
name: JNLPBA
domain: biomed
task: ner
lang: en
num_examples: 22402
size_in_bytes: 3742335
size_in_human_bytes: 3.57 MiB
data_files_modified: '2022-02-26 03:02:57'
info_updated: '2022-02-26 03:06:01'
data_files:
  train: JNLPBA-train.csv
  dev: JNLPBA-dev.csv
  test: JNLPBA-test.csv
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
