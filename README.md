# Introduction

This repository contains additional reference translations for the WMT'14 En-De (newstest2014) and WMT'19 En-Ru (newstest2019) test sets as described in the paper:
[On The Evaluation of Machine Translation Systems Trained With Back-Translation](https://arxiv.org/abs/1908.05204).


# Content
- newstest2014-deen.src.de : 500 German-original sentences randomly sampled from German-original part of newstest2014
- newstest2014-deen.tgt.en : Official translation to English of the 500 German-original sentences done by WMT
- newstest2014-deen.r1.en  : Additional translation to English of the 500 German-original sentences done by professional translation on the sentence level
- newstest2014-deen.r1.r1.de : Translations to German of the sentences from newstest2014-deen.r1.en, done by professional translation on the sentence level
- newstest2014-ende.src.en : 500 English-original sentences randomly sampled from English-original part of newstest2014
- newstest2014-ende.tgt.de : Official translation to German of the 500 English-original sentences done by WMT
- newstest2014-ende.r1.de  : Additional translation to German of the 500 English-original sentences done by professional translation on the sentence level
- newstest2014-ende.r1.r1.en : Translations to English of the sentences from newstest2014-ende.r1.de, done by professional translation on the sentence level

- newstest2019-ruen.src.ru : 500 Russian-original sentences randomly sampled from Russian-original part of newstest2019
- newstest2019-ruen.tgt.en : Official translation to English of the 500 Russian-original sentences done by WMT
- newstest2019-ruen.r1.en  : Additional translation to English of the 500 Russian-original sentences done by professional translation on the sentence level
- newstest2019-ruen.r1.r1.ru : Translations to Russian of the sentences from newstest2019-ruen.r1.en, done by professional translation on the sentence level
- newstest2019-enru.src.en : 500 English-original sentences randomly sampled from English-original part of newstest2019
- newstest2019-enru.tgt.ru : Official translation to Russian of the 500 English-original sentences done by WMT
- newstest2019-enru.r1.ru  : Additional translation to Russian of the 500 English-original sentences done by professional translation on the sentence level
- newstest2019-enru.r1.r1.en : Translations to English of the sentences from newstest2019-enru.r1.ru, done by professional translation on the sentence level


# Citation

If you use the data in your paper, then please cite it as:

```
@inproceedings{edunov2019evaluation,
  author    = {Sergey Edunov and Myle Ott and Marc'Aurelio Ranzato and Michael Auli},
  title     = {On The Evaluation of Machine Translation Systems Trained With Back-Translation},
  booktitle = {Association for Computational Linguistics},
  year      = 2020,
}
```

# License
The dataset is licenced under CC-by-NC, see the LICENSE file for details.



