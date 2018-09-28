# Perplexity (lower is better) of Neural Language Models

Exclude scores of methods using test data statistics such as cache mechanism

updated at 2018/9/28

### Penn Treebank (PTB)


Publication | Model | Parameters | Valid | Test 
----------- | ----- | ---------- | ----- | ----
[Mikolov and Zweig '12](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/rnn_ctxt.pdf) | RNN | - | 124.7
[Mikolov and Zweig '12](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/rnn_ctxt.pdf) | RNN + LDA + Kneser-Ney smoothing | - | 98.3
[Zaremba et al. '14](https://arxiv.org/pdf/1409.2329.pdf) | LSTM (medium) | 20M | 86.2 | 82.7
[Gal and Ghahramani. '16](https://arxiv.org/pdf/1512.05287.pdf) | Variational LSTM (medium) + Word Tying | 20M | 81.8 ± 0.2 | 79.2 ± 0.1
[Kim et al. '16](https://arxiv.org/pdf/1508.06615.pdf) | CharCNN + LSTM | 19M | - | 78.9
[Zaremba et al. '14](https://arxiv.org/pdf/1409.2329.pdf) | LSTM (large) | 66M | 82.2 | 78.4
[Gal and Ghahramani. '16](https://arxiv.org/pdf/1512.05287.pdf) | Variational LSTM (large) + Word Tying | 66M | 77.3 ± 0.2 | 75.0 ± 0.1
[Gal and Ghahramani. '16](https://arxiv.org/pdf/1512.05287.pdf) | Variational LSTM (large) + Word Tying + MC dropout | 66M | - | 73.4 ± 0.0
[Zaremba et al. '14](https://arxiv.org/pdf/1409.2329.pdf) | LSTM (large) **Ensemble** | 2.5G | 71.9 | 68.7
[Zilly et al. '17](https://arxiv.org/pdf/1607.03474.pdf) | Variational RHN + Word Tying | 23M | 67.9 | 65.4
[Takase et al. '17](http://aclweb.org/anthology/I/I17/I17-2008.pdf) | Variational RHN + Word Tying + IOG | 29M | 67.0 | 64.4
[Zoph and Le '17](https://arxiv.org/pdf/1611.01578.pdf) | Neural Architecture Search + Word Tying | 54M | - | 62.4
[Takase et al. '17](http://aclweb.org/anthology/I/I17/I17-2008.pdf) | Variational RHN + IOG **Ensemble** | 326M | 64.1 | 61.4
[Melis et al. '18](https://arxiv.org/pdf/1707.05589.pdf) | LSTM with skip connections | 24M | 60.9 | 58.3
[Merity et al '18](https://arxiv.org/pdf/1708.02182.pdf) | AWD-LSTM | 24M | 60.0 | 57.3
[Yang et al '18](https://arxiv.org/pdf/1711.03953.pdf) | AWD-LSTM-MoS | 22M | 56.54 | 54.44
[Gong et al '18](https://arxiv.org/pdf/1809.06858.pdf) | AWD-LSTM-MoS + FRAGE | 22M | 55.52 | 53.31
[Takase et al '18](https://arxiv.org/pdf/1808.10143.pdf) | AWD-LSTM-DOC | 23M | 54.12 | 52.38
[Takase et al '18](https://arxiv.org/pdf/1808.10143.pdf) | AWD-LSTM-DOC **Ensemble** | 114M | 48.63 | 47.17

