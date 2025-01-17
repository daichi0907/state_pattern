# 課題：ステートパターンで書き直そう
「クレジット情報」-「タイトル」-「オープニング」-「デモ」の表示を一定時間で繰り返すプログラムがあります。

gotoは、ありえないので、挙動を変えずに、ステートパターンを使って書き直してください。

![現在のプログラムの結果](result.png)


# 取り組み方
* 本プロジェクトをforkして、取り組んでください。
  * README.mdを書き換えて、ビルドの状態のバッチを自分のアカウントに差し替えておくこと
* 「src」ディレクトリの「src.cpp」を書き替えてください。
* 納得できるところまでできたら、「tpu-game-2021/state_pattern」のmainブランチにプルリクを出してください
* よくわからない場合は、何が分からないか（どこまでわかったか）README.mdのどこかに記載してください


# ビルド状態
[![MSBuild](https://github.com/daichi0907/state_pattern/actions/workflows/msbuild.yml/badge.svg)](https://github.com/daichi0907/state_pattern/actions/workflows/msbuild.yml)

（このファイルの上の行の[tpu-game-2021]の部分(2か所)を自分のアカウント名に修正してください）

# わからなかったところ
* 今回列挙と分岐のステートパターンを使ってプログラムを書き直したのですが、「状態」のパターン以降の内容がいまいち理解できずその手法での書き直しができませんでした。
  今回のプログラムの場合はどのように書き直せばよかったのか教えていただけると助かります。
* gotoの部分を挙動を変えずに書き直すにはwhileで無限ループにするやり方で正しかったのか疑問に感じました。他の方法もあるようでしたら教えていただけるとありがたいです。

# 〆切
5/24(月)
