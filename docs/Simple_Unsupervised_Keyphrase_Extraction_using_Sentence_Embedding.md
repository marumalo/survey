# Simple Unsupervised Keyphrase Extraction using Sentence Embedding

教師なしのキーフレーズ抽出手法を提案。文書ベクトルとフレーズベクトルを同じベクトル空間上にマップし、以下の2つの方法でキーフレーズ候補をランキングする。

- 文書ベクトルとフレーズベクトルのコサイン類似度 (EmbedRank)
- EmbedRank + 抽出されたキーフレーズ中の多様性を考慮 (EmbedRank++)

多様性を考慮することにより、ユーザによる評価において、高いスコアを獲得。

<br>

![embedrank](https://user-images.githubusercontent.com/53220859/63406315-7a3a0400-c424-11e9-9a5b-60df4595421c.png)

※ 図は元論文から引用。

<br>

## 文献情報

- 著者: Kamil Bennani-Smires, Claudiu Musat, Andreaa Hossmann, Michael Baeriswyl, and Martin Jaggi
- リンク: [https://arxiv.org/pdf/1801.04470.pdf](https://arxiv.org/pdf/1801.04470.pdf)