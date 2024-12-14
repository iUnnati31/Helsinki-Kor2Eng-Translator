---
library_name: transformers
license: apache-2.0
base_model: Helsinki-NLP/opus-mt-ko-en
tags:
- translation
- generated_from_trainer
metrics:
- bleu
model-index:
- name: korean-to-english-translator
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# korean-to-english-translator

This model is a fine-tuned version of [Helsinki-NLP/opus-mt-ko-en](https://huggingface.co/Helsinki-NLP/opus-mt-ko-en) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 0.7533
- Model Preparation Time: 0.0018
- Bleu: 56.0499

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 2e-05
- train_batch_size: 4
- eval_batch_size: 4
- seed: 42
- optimizer: Use OptimizerNames.ADAMW_TORCH with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: linear
- num_epochs: 3

### Training results



### Framework versions

- Transformers 4.47.0
- Pytorch 2.5.1+cu124
- Datasets 3.2.0
- Tokenizers 0.21.0
