---
license: llama3.3
datasets:
- HuggingFaceTB/finemath
- hollywoodfrancis/francis_trained
language:
- en
- pt
metrics:
- accuracy
- code_eval
base_model:
- meta-llama/Llama-3.3-70B-Instruct
new_version: meta-llama/Llama-3.3-70B-Instruct
library_name: adapter-transformers
tags:
- finance
- code
---