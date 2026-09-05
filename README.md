# pytorch-by-hand

note連載「**3分で学ぶPyTorch**」基礎編の演習ノートブックです。

解説を読んで分かった気になる部分と、実際に自分で書ける部分は別物です。
ここでは穴埋め形式で、PyTorch のコードを一行ずつ手で書いていきます。

記事はこちら → [マガジン「3分で学ぶPyTorch」](https://note.com/technosend/m/m84d841b6d067)

## 使い方

1. **演習**列の Open in Colab を押す
2. ノートブックの `【TASK】` と書かれた箇所を埋める
3. 上から順に実行する

**解答（ans）は詰まったときだけ見てください。** 読んで分かった気になる部分と、
自分で書ける部分は別物なので、一度詰まったほうが結局は早く進みます。

環境構築は要りません。書き換えたものを残したいときは、Colab のメニューから
「ドライブにコピーを保存」を選んでください。

## 演習

### ① MLP を手で書く — 分類と回帰

| | 演習 | 解答 |
|---|---|---|
| Section 1 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/mlp/01_mlp_sec01_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/mlp/01_mlp_sec01_ans.ipynb) |
| Section 2 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/mlp/01_mlp_sec02_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/mlp/01_mlp_sec02_ans.ipynb) |

### ② CNN を手で書く — MNIST から CIFAR-10 へ

| | 演習 | 解答 |
|---|---|---|
| Section 1 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/cnn/02_cnn_sec01_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/cnn/02_cnn_sec01_ans.ipynb) |
| Section 2 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/cnn/02_cnn_sec02_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/cnn/02_cnn_sec02_ans.ipynb) |

### ③ RNN を手で書く — 気温予測と時系列分類

| | 演習 | 解答 |
|---|---|---|
| Section 1 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/rnn/03_rnn_sec01_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/rnn/03_rnn_sec01_ans.ipynb) |
| Section 2 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/rnn/03_rnn_sec02_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/rnn/03_rnn_sec02_ans.ipynb) |

### ④ 自然言語処理を手で書く — 文章生成と文章分類

| | 演習 | 解答 |
|---|---|---|
| Section 1 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/nlp/04_nlp_sec01_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/nlp/04_nlp_sec01_ans.ipynb) |
| Section 2 | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/nlp/04_nlp_sec02_task.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akh1r0ck/pytorch-by-hand/blob/main/nlp/04_nlp_sec02_ans.ipynb) |

## 動作環境

Google Colab で動作を確認しています。PyTorch 2.x 系を前提にしています。

## 発展編

実務水準のトレーニングループ、転移学習、Transformer のスクラッチ実装などを扱う**発展編**は、
note の有料記事として公開しています。演習ノートブックは記事に添付しています。

## ライセンス

学習用途で自由に使ってください。
