# EN-to-FR Transformer from Scratch

PyTorchを用いて、アーキテクチャ（Self-Attention / Cross-Attention）から自作した英語 ➔ フランス語翻訳モデルです。

## 概要
- **モデル**: Transformer (Encoder-Decoder) 自作実装
- **データセット**: OPUS Books (en-fr)
- **トークナイザー**: bert-base-multilingual-cased

## 環境構築・実行方法
```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
pip install -r requirements.txt
python train.py
