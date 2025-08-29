This is the official github repository for `Summarize-Exemplify-Reflect: Data-driven Insight Distillation Empowers LLMs for Few-shot Tabular Classification' accepted at EMMLP 2025 Findings.
<img width="1528" height="774" alt="image" src="https://github.com/user-attachments/assets/866530f2-c802-43b6-8854-e62f39f32c89" />

# Paper Link
To be updated
# Data
The data is stored in the datasets_serialized/ folder. It contains serialized data in the .jsonl. The records are generated using the dataset_all.py in the summaryboost/ folder.
# Code
The code is stored in the summaryboost/ folder. The .json and .txt files are used to construct the prompts in our experiments. main.py is the algorithm file.
# Update 07/24
Main updates: add the iterative error rule summarization mechanism, also add resampling.

The main iteration file is stored in ours/iteration_ours.py.

Also update the rules.py by saving the scores and entropy together. The old version is stored in rules_old.py

For selection_strategy.py, add the resampling function.

# Cite
To be updated
