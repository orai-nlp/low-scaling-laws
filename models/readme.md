# Models

Description

|           | aka    | Layers | HH     | INT  | Heads | Non-embedding parameters | Parameters |
|-----------|--------|--------|--------|------|-------|--------------------------|------------|
| BERT_124M | base   | 12     | 768    | 3072 | 12    | 86M                      | 124M       |
| BERT_51M  | medium | 8      | 512    | 2048 | 8     | 25M                      | 51M        |
| BERT_16M  | mini   | 4      | 256    | 1024 | 4     | 3M                       | 16M        |

HH:hidden dimensions. INT: intermediate layer dimension. Heads: attention heads.

config files: BERT_124M, BERT_51M, BERT_16M


### Basque
vocab files: eu5M eu25M eu125M

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-eu-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_5M/pytorch_model.bin)  |  [bert-base-eu-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_25M/pytorch_model.bin)  |   [bert-base-eu-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_125M/pytorch_model.bin) |
| BERT_51M   |  [bert-medium-eu-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_5M/pytorch_model.bin)  |  [bert-medium-eu-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_25M/pytorch_model.bin)  |   [bert-medium-eu-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_125M/pytorch_model.bin) |
| BERT_16M   | [bert-mini-eu-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_5M/pytorch_model.bin)  |  [bert-mini-eu-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_25M/pytorch_model.bin)  |   [bert-mini-eu-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_125M/pytorch_model.bin) |

### Spanish

vocab files: es5M es25M es125M

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |                                  |                                   |                                       |
| BERT_51M   |                                  |                                   |                                       |
| BERT_16M   |                                  |                                   |                                       |

### Swahili

vocab files: sw5M sw25M sw125M

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |                                  |                                   |                                       |
| BERT_51M   |                                  |                                   |                                       |
| BERT_16M   |                                  |                                   |                                       |

BERT_124M (which is new SotA in some tasks) and BERT_51M (both trained on 125M token corpus) are also available at [HF🤗 Datasets](https://huggingface.co/datasets/orai-nlp/bert-base-sw)!

### Finnish

vocab files: fi5M fi25M fi125M

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |                                  |                                   |                                       |
| BERT_51M   |                                  |                                   |                                       |
| BERT_16M   |                                  |                                   |                                       |
