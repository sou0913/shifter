# シフト自動作成アプリの作成

## 概要
- 入力した条件に従い、一月分のシフトを自動で作成します。

## 動作環境
python3.6.1

## 使用技術
- Pythonと、フレームワークtkinterを用いました。

## 制作理由
- シフト作成は前職で「もっと効率化できないか」と感じていたところだった。
- Pythonが行列の扱いに長けている印象をもち、この機会に使用してみたいと感じた。

## 機能について
- 条件を入力すると、それに従ったシフト表が作成されます。インターフェイスはtkinterを用いました。

<a href="https://gyazo.com/69512bda0b2970b76b54caed8feec910"><img src="https://i.gyazo.com/69512bda0b2970b76b54caed8feec910.gif" alt="Image from Gyazo" width="400"/></a>

<br>

- 休日の最大出勤人数、最大連勤数といった条件を入力することができ、かゆいところに手の届くシフトを作成できます。

- また、フォーマットに従い、excelファイルにあらかじめ文字を入力しておくと、その部分を休みにしたシフトを作成できます。

<a href="https://gyazo.com/f59d89b5b0b28630c9be374f0653b48c"><img src="https://i.gyazo.com/f59d89b5b0b28630c9be374f0653b48c.gif" alt="Image from Gyazo" width="400"/></a>


<a href="https://gyazo.com/fb61cb41c103a4f0bbac3fbdd68737d2"><img src="https://i.gyazo.com/fb61cb41c103a4f0bbac3fbdd68737d2.gif" alt="Image from Gyazo" width="400"/></a>

<br>

- 制作したシフト表は自動でExcelに出力されます。

<a href="https://gyazo.com/302be05ee3a24fe64ddfd421a3284759"><img src="https://i.gyazo.com/302be05ee3a24fe64ddfd421a3284759.gif" alt="Image from Gyazo" width="400"/></a>

<br>

Excelで出力できるようにしたのは、私の以前の職場ではシフトの提出がExcelファイルだった、という背景があります。

<br>

## 制作で学んだこと
- Pythonの基本的な文法を理解することができました。
- 最初に作成したものは、計算量が大きすぎて動きませんでした。そこから計算量を減らす工夫をすることで、実用的なものに仕上がったのではないかと思います。
