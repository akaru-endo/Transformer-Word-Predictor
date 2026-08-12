# EN-to-FR Transformer from Scratch

PyTorchを用いて、アーキテクチャ（Self-Attention / Cross-Attention）から自作した英語 ➔ フランス語翻訳モデルです。

## 概要
- **モデル**: Transformer (Encoder-Decoder) 自作実装
- **データセット**: OPUS Books (en-fr)
- **トークナイザー**: bert-base-multilingual-cased

## プロジェクトの目的・特徴
本プロジェクトは、Hugging Faceなどの既存の構築済みモデルライブラリに頼るのではなく、**Transformerアーキテクチャの内部理論と実装（Self-Attention, Cross-Attention, Positional Encoding等）を深層レベルで理解し、PyTorchでゼロから（From Scratch）組み上げる**ことに重きを置いて作成しました。

軽量なモデル構造および学習設定としているため、翻訳の精度自体は実用レベルに達していませんが、Transformerのメカニズムを学ぶための基盤コードとして構築しています。

## 環境構築・実行方法
```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
pip install -r requirements.txt
python train.py
