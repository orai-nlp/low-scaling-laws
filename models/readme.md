# Models

Description

|           | aka    | Layers | HH     | INT  | Heads | Non-embedding parameters | Parameters |
|-----------|--------|--------|--------|------|-------|--------------------------|------------|
| BERT_124M | base   | 12     | 768    | 3072 | 12    | 86M                      | 124M       |
| BERT_51M  | medium | 8      | 512    | 2048 | 8     | 25M                      | 51M        |
| BERT_16M  | mini   | 4      | 256    | 1024 | 4     | 3M                       | 16M        |

HH:hidden dimensions. INT: intermediate layer dimension. Heads: attention heads.

config files: 

* BERT_124M: [base-config.json](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_125M/config.json)
* BERT_51M: [medium-config.json](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_125M/config.json)
* BERT_16M: [mini-config.json](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_125M/config.json)


### Basque
vocab files: [eu5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_5M/vocab.txt) [eu25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_25M/vocab.txt) [eu125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_125M/vocab.txt)

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-eu-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_5M/pytorch_model.bin)  |  [bert-base-eu-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_25M/pytorch_model.bin)  |   [bert-base-eu-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_eu_125M/pytorch_model.bin) |
| BERT_51M   |  [bert-medium-eu-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_5M/pytorch_model.bin)  |  [bert-medium-eu-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_25M/pytorch_model.bin)  |   [bert-medium-eu-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_eu_125M/pytorch_model.bin) |
| BERT_16M   | [bert-mini-eu-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_5M/pytorch_model.bin)  |  [bert-mini-eu-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_25M/pytorch_model.bin)  |   [bert-mini-eu-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_eu_125M/pytorch_model.bin) |

### Spanish

vocab files: [es5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_es_5M/vocab.txt) [es25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_es_25M/vocab.txt) [es125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_es_125M/vocab.txt)

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-es-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_es_5M/pytorch_model.bin)  |  [bert-base-es-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_es_25M/pytorch_model.bin)  |   [bert-base-es-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_es_125M/pytorch_model.bin) |
| BERT_51M   |  [bert-medium-es-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_es_5M/pytorch_model.bin)  |  [bert-medium-es-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_es_25M/pytorch_model.bin)  |   [bert-medium-es-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_es_125M/pytorch_model.bin) |
| BERT_16M   | [bert-mini-es-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_es_5M/pytorch_model.bin)  |  [bert-mini-es-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_es_25M/pytorch_model.bin)  |   [bert-mini-es-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_es_125M/pytorch_model.bin) |

### Swahili

vocab files: [sw5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_sw_5M/vocab.txt) [sw25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_sw_25M/vocab.txt) [sw125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_sw_125M/vocab.txt)

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-sw-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_sw_5M/pytorch_model.bin)  |  [bert-base-sw-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_sw_25M/pytorch_model.bin)  |   [bert-base-sw-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_sw_125M/pytorch_model.bin) |
| BERT_51M   |  [bert-medium-sw-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_sw_5M/pytorch_model.bin)  |  [bert-medium-sw-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_sw_25M/pytorch_model.bin)  |   [bert-medium-sw-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_sw_125M/pytorch_model.bin) |
| BERT_16M   | [bert-mini-sw-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_sw_5M/pytorch_model.bin)  |  [bert-mini-sw-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_sw_25M/pytorch_model.bin)  |   [bert-mini-sw-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_sw_125M/pytorch_model.bin) |

BERT_124M (which is new SotA in some tasks) and BERT_51M (both trained on 125M token corpus) are also available at [HF🤗 Datasets](https://huggingface.co/datasets/orai-nlp/bert-base-sw)!

### Finnish

vocab files: [fi5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_fi_5M/vocab.txt) [fi25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_fi_25M/vocab.txt) [fi125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_fi_125M/vocab.txt)

|            |   5M                             |   25M                             |   125M                                |
|------------|----------------------------------|-----------------------------------|---------------------------------------|
| BERT_124M  |  [bert-base-fi-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_fi_5M/pytorch_model.bin)  |  [bert-base-fi-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_fi_25M/pytorch_model.bin)  |   [bert-base-fi-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_base_fi_125M/pytorch_model.bin) |
| BERT_51M   |  [bert-medium-fi-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_fi_5M/pytorch_model.bin)  |  [bert-medium-fi-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_fi_25M/pytorch_model.bin)  |   [bert-medium-fi-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_medium_fi_125M/pytorch_model.bin) |
| BERT_16M   | [bert-mini-fi-5M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_fi_5M/pytorch_model.bin)  |  [bert-mini-fi-25M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_fi_25M/pytorch_model.bin)  |   [bert-mini-fi-125M](https://storage.cloud.google.com/elhuyar/low-scaling-laws/models/bert_mini_fi_125M/pytorch_model.bin) |
