# Sequence-to-sequence Pre-training with Data Augmentation for Sentence Rewriting
文書き換えタスク(論文では、文法誤り訂正とスタイル変換)におけるデータ拡張手法を提案。生成した擬似データと教師データを同時に用いて学習させるのではなく、擬似データを学習したのちに、教師データでfine-tuningを行っている。

擬似データは逆翻訳によって生成を行うが、言語モデル(文法誤り訂正)や二値分類器(スタイル変換)を用いてフィルタリングすることで、学習に効果的なデータのみを抽出している。

<p align="center">
<img src=https://user-images.githubusercontent.com/53220859/64955647-bf3a4480-d8c3-11e9-8a5a-c6a29736db25.png width=600pt>
</p>

## 文献情報
- 著者: Yi Zhang, Tao Ge, Furu Wei, Ming Zhou and Xu Sun
- リンク: [https://arxiv.org/abs/1909.06002](https://arxiv.org/abs/1909.06002)
- 学会: arXiv2019






