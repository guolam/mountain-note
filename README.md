# 山ノート　（MOUNTAIN NOTE）

## DEMO

  -   https://guolam.github.io/mountain-note/mountain_note_first.html

## 紹介と使い方

  - 山であったこと：登った日、登った山、食べた山飯、山の写真一枚を記録する。

  - 記録した履歴をずっと貯めておく

## 工夫した点

  - ローカルストレージ自体は文字列のみ対応しますが、工夫して、写真を入れられるようにしました。  やり方：htmlの列をjsで反映して、<img src>の方法で、文字列を写真として反映するようにしてみました。


  ‐ 写真を入れるだけではなくて、写真自体がギャラリーのように、ずっと繰り返して見れるような仕組みにしました。

## 苦戦した点

  - 履歴を残すこと＝配列にオブジェクトに入れるのに苦戦しました。
  - そして、jSONデータの取り出し方にも一苦労でした。
  ‐ 配列とオブジェクトの概念自体が1週間くらいかけてやっと理解できた。

## 参考にした web サイトなど

  ー　*localStorageで複数のデータを保存する*
  https://www.tam-tam.co.jp/tipsnote/javascript/post5978.html

  - LAB生のヒーくんにめちゃ教えていただきました。
  - 大事な概念：
  - 配列の中に、オブジェクトを入れられます。
  - JSONデータを一個一個取り出して、文字列にしたら、表示される。


