# Awesome-Speculative-Decoding

## Resources
A collection of papers of Speculative Decoding

### Surveys
**Unlocking Efficiency in Large Language Model Inference: A Comprehensive Survey of Speculative Decoding**<br />
Heming Xia, Zhe Yang, Qingxiu Dong, Peiyi Wang, Yongqi Li, Tao Ge, Tianyu Liu, Wenjie Li, Zhifang Sui. [[paper](https://arxiv.org/abs/2401.07851)]
<div align=center><img src="./img/taxonomy.png" width="100%" height="80%" /></div>

**Beyond the Speculative Game: A Survey of Speculative Execution in Large Language Models**<br />
Chen Zhang, Zhuorui Liu, Dawei Song. [[paper](https://arxiv.org/abs/2404.14897)]

### Lossless
To better understand lossless acceleration, please first learn about *Reject Sampling*.

> Blockwise Decoding
**Blockwise Parallel Decoding for Deep Autoregressive Models** (NIPS 2018)<br />
Mitchell Stern, Noam Shazeer, Jakob Uszkoreit. [[paper](https://arxiv.org/abs/1811.03115)]

> SpecDec
**Speculative Decoding: Exploiting Speculative Execution for Accelerating Seq2seq Generation**<br />
Heming Xia, Tao Ge, Peiyi Wang, Si-Qing Chen, Furu Wei, Zhifang Sui [[paper](https://arxiv.org/abs/2203.16487)]

> Reject Samping
**Accelerating Large Language Model Decoding with Speculative Sampling**<br />
Charlie Chen, Sebastian Borgeaud, Geoffrey Irving, Jean-Baptiste Lespiau, Laurent Sifre, John Jumper. [[paper](https://arxiv.org/abs/2302.01318)]

**Fast Inference from Transformers via Speculative Decoding** (ICML 2023)<br />
Yaniv Leviathan, Matan Kalman, Yossi Matias. 
[[paper](https://proceedings.mlr.press/v202/leviathan23a.html)]

> EAGLE
**EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty**<br />
Yuhui Li, Fangyun Wei, Chao Zhang, Hongyang Zhang. [[paper](https://arxiv.org/abs/2401.15077)][[code](https://github.com/SafeAILab/EAGLE)]

> EAGLE-2
**EAGLE-2: Faster Inference of Language Models with Dynamic Draft Trees**<br />
Yuhui Li, Fangyun Wei, Chao Zhang, Hongyang Zhang. [[papaer](https://arxiv.org/abs/2406.16858)][[code](https://github.com/SafeAILab/EAGLE)]

### Approximate
> Medusa
**Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads**<br />
Tianle Cai, Yuhong Li, Zhengyang Geng, Hongwu Peng, Jason D. Lee, Deming Chen, Tri Dao. [[paper](https://arxiv.org/abs/2401.10774)][[code](https://github.com/FasterDecoding/Medusa)]

