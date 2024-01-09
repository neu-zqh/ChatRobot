---
license: other
library_name: peft
tags:
- llama-factory
- lora
- generated_from_trainer
base_model: D:\Model\bloom-560m
model-index:
- name: train_2023-12-29-10-53-19
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# train_2023-12-29-10-53-19

This model is a fine-tuned version of [D:\Model\bloom-560m](https://huggingface.co/D:\Model\bloom-560m) on the oaast_sft_zh dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 4
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: cosine
- num_epochs: 3.0
- mixed_precision_training: Native AMP

### Training results



### Framework versions

- PEFT 0.7.1
- Transformers 4.36.0
- Pytorch 2.1.0+cu121
- Datasets 2.15.0
- Tokenizers 0.15.0