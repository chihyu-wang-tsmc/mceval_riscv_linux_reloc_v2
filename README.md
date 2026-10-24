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
  - name: compiler_pic_asm
    dtype: string
  - name: pic_object_asm
    dtype: string
  - name: program_asm_v2
    dtype: string
  splits:
  - name: O0
    num_bytes: 2244038
    num_examples: 50
  - name: O2
    num_bytes: 1556427
    num_examples: 50
  download_size: 1011800
  dataset_size: 3800465
configs:
- config_name: default
  data_files:
  - split: O0
    path: data/O0-*
  - split: O2
    path: data/O2-*
---
