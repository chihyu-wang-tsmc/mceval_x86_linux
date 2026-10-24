---
dataset_info:
  features:
  - name: task_name
    dtype: string
  - name: source_code
    dtype: string
  - name: compiler_asm
    dtype: string
  - name: object_asm
    dtype: string
  - name: shared_asm
    dtype: string
  - name: program_asm
    dtype: string
  splits:
  - name: O0
    num_bytes: 1255136
    num_examples: 50
  - name: O2
    num_bytes: 1048163
    num_examples: 50
  download_size: 606540
  dataset_size: 2303299
configs:
- config_name: default
  data_files:
  - split: O0
    path: data/O0-*
  - split: O2
    path: data/O2-*
---
