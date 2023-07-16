# Models

Here you can download our 36 models of 3 different model sizes (see Table below) and trained for 3 different pretraining corpora (5M-25M-125M) for each language.

|           | aka    | Layers | HH     | INT  | Heads | Non-embedding parameters | Parameters |
|-----------|--------|--------|--------|------|-------|--------------------------|------------|
| BERT_124M | base   | 12     | 768    | 3072 | 12    | 86M                      | 124M       |
| BERT_51M  | medium | 8      | 512    | 2048 | 8     | 25M                      | 51M        |
| BERT_16M  | mini   | 4      | 256    | 1024 | 4     | 3M                       | 16M        |

HH:hidden dimensions. INT: intermediate layer dimension. Heads: attention heads.

### Basque

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-eu-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_eu_5M.tar.gz)  |  [bert-base-eu-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_eu_25M.tar.gz)  |   [bert-base-eu-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_eu_125M.tar.gz) |
| BERT_51M   |  [bert-medium-eu-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_eu_5M.tar.gz)  |  [bert-medium-eu-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_eu_25M.tar.gz)  |   [bert-medium-eu-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_eu_125M.tar.gz) |
| BERT_16M   | [bert-mini-eu-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_eu_5M.tar.gz)  |  [bert-mini-eu-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_eu_25M/pytorch_model.bin)  |   [bert-mini-eu-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_eu_125M.tar.gz) |

### Spanish

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-es-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_es_5M.tar.gz)  |  [bert-base-es-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_es_25M.tar.gz)  |   [bert-base-es-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_es_125M.tar.gz) |
| BERT_51M   |  [bert-medium-es-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_es_5M.tar.gz)  |  [bert-medium-es-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_es_25M.tar.gz)  |   [bert-medium-es-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_es_125M.tar.gz) |
| BERT_16M   | [bert-mini-es-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_es_5M.tar.gz)  |  [bert-mini-es-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_es_25M.tar.gz)  |   [bert-mini-es-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_es_125M.tar.gz) |

### Swahili

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-sw-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_sw_5M.tar.gz)  |  [bert-base-sw-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_sw_25M.tar.gz)  |   [bert-base-sw-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_sw_125M.tar.gz)  |
| BERT_51M   |  [bert-medium-sw-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_sw_5M.tar.gz)  |  [bert-medium-sw-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_sw_25M.tar.gz)  |   [bert-medium-sw-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_sw_125M.tar.gz) |
| BERT_16M   | [bert-mini-sw-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_sw_5M.tar.gz)  |  [bert-mini-sw-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_sw_25M.tar.gz)  |   [bert-mini-sw-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_sw_125M.tar.gz) |

[bert-base-sw-125M](https://huggingface.co/orai-nlp/bert-base-sw) (SotA) and [bert-medium-sw-125M](https://huggingface.co/orai-nlp/bert-medium-sw) are also available at HF🤗! 

### Finnish

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-fi-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_fi_5M.tar.gz)  |  [bert-base-fi-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_fi_25M.tar.gz)  |   [bert-base-fi-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_base_fi_125M.tar.gz) |
| BERT_51M   |  [bert-medium-fi-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_fi_5M.tar.gz)  |  [bert-medium-fi-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_fi_25M.tar.gz)  |   [bert-medium-fi-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_medium_fi_125M.tar.gz) |
| BERT_16M   | [bert-mini-fi-5M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_fi_5M.tar.gz)  |  [bert-mini-fi-25M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_fi_25M.tar.gz)  |   [bert-mini-fi-125M](https://storage.googleapis.com/elhuyar/low-scaling-laws/models/bert_mini_fi_125M.tar.gz) |
