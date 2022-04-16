# tplinker_bert4torch
基于bert4torch框架，tplinker/tplinker_plus/tplinker_ner的pytorch简洁实现
1. 本脚本全部基于[bert4torch](https://github.com/Tongjilibo/bert4torch)框架，主要是用pytorch复现[bert4keras](https://github.com/bojone/bert4keras)以及各种实例
2. 如果链接打不开，可能是因为源文件更新，可直接访问[bert4torch_example](https://github.com/Tongjilibo/bert4torch/tree/master/examples)

---
- [task_relation_extraction_tplinker.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/relation_extraction/task_relation_extraction_tplinker.py)：任务例子，tplinker关系抽取[TPLinker](https://github.com/131250208/TPlinker-joint-extraction)。
- [task_relation_extraction_tplinker_plus.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/relation_extraction/task_relation_extraction_tplinker_plus.py)：任务例子，tplinker关系抽取[TPLinkerPlus](https://github.com/131250208/TPlinker-joint-extraction)。
- [task_sequence_labeling_ner_tplinker_plus.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/sequence_labeling/task_sequence_labeling_ner_tplinker_plus.py)：任务例子，ner例子，改造了关系抽取[TPLinker](https://github.com/131250208/TPlinker-joint-extraction)
