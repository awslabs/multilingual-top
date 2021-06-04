## Multilingual TOP dataset for semantic parsing

This repository contains the multilingual TOP dataset created in the paper:

_"Multilingual Neural Semantic Parsing for Low-Resourced Languages". Menglin Xia, Emilio Monti. *SEM2021._

Please cite our paper if you use this dataset.

### Description

The multilingual TOP dataset is a multilingual semantic parsing dataset in English, Italian and Japanese, based on the public Facebook Task Oriented
Parsing (TOP) dataset in English. The original TOP dataset can be found here: [\[paper\]](https://research.fb.com/publications/semantic-parsing-for-task-oriented-dialog-using-hierarchical-representations/) [\[data\]](http://fb.me/semanticparsingdialog).

The Multilingual TOP dataset contains ˜30k training and validation data and ˜8k test data in English, Italian and Japanese. The Italian and Japanese training and validation data are machine-translated from English TOP, and the test data are manually translated.

### Directories

The `raw_test_data` directory contains the manually translated test sets in Italian and Japanese in xml.

The `processed_data` directory contains the processed multilingual TOP semantic parsing data (train, dev, test) used in the paper.

## License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the LICENSE file.

The sample code within this documentation is made available under the MIT-0 license. See the LICENSE-SAMPLECODE file.
