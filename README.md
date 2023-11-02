# Supplementary Material  Performance Similarity DLfM 2023

This repository contains data and evaluation code of the listening test in the publication ["Sounding Out Reconstruction Error-Based Evaluation of Generative Models of Expressive Performance"](https://dl.acm.org/doi/10.1145/3625135.3625141), accepted at DLfM 2023.

The audio files the participants listened to are hosted in a separate [repository](https://gitlab.com/silter/performance) with the following main paths:
- audio/MP3_OUT_normalized -> randomized versions
- audio/MP3_4x22_normalized -> original versions

## Acknowledgments

This work is supported by the European Research Council (ERC) under the EU’s Horizon 2020 research & innovation programme, grant agreement No. 10101937 (”Wither Music?”).

## Cite Us

If you use this work please cite us:

```
@inproceedings{10.1145/3625135.3625141,
author = {Peter, Silvan David and Cancino-Chac\'{o}n, Carlos Eduardo and Karystinaios, Emmanouil and Widmer, Gerhard},
title = {Sounding Out Reconstruction Error-Based Evaluation of Generative Models of Expressive Performance},
year = {2023},
isbn = {9798400708336},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3625135.3625141},
doi = {10.1145/3625135.3625141},
abstract = {Generative models of expressive piano performance are usually assessed by comparing their predictions to a reference human performance. A generative algorithm is taken to be better than competing ones if it produces performances that are closer to a human reference performance. However, expert human performers can (and do) interpret music in different ways, making for different possible references, and quantitative closeness is not necessarily aligned with perceptual similarity, raising concerns about the validity of this evaluation approach. In this work, we present a number of experiments that shed light on this problem. Using precisely measured high-quality performances of classical piano music, we carry out a listening test indicating that listeners can sometimes perceive subtle performance difference that go unnoticed under quantitative evaluation. We further present tests that indicate that such evaluation frameworks show a lot of variability in reliability and validity across different reference performances and pieces. We discuss these results and their implications for quantitative evaluation, and hope to foster a critical appreciation of the uncertainties involved in quantitative assessments of such performances within the wider music information retrieval (MIR) community.},
booktitle = {Proceedings of the 10th International Conference on Digital Libraries for Musicology},
pages = {58–66},
numpages = {9},
keywords = {Evaluation, Validity, Performance, Listening Study, Expression},
location = {Milan, Italy},
series = {DLfM '23}
}
```