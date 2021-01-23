# LOVOT STUDY でつくったプログラム集

## 共通：LOVOT の名前を設定する

他の人が作った LOVOT STUDY ファイル（拡張子が `sb3` ファイル，以下「`sb3`ファイル」と呼びます）を読み込んだとき，LOVOT に接続するためのブロックに LOVOT の名前が設定されていないので，LOVOT の名前を設定し，`sb3`ファイルを保存し直してください。

<p align="center">
    <a href="https://gyazo.com/3580213505f3c60753fb8bf356d90702"><img src="https://i.gyazo.com/3580213505f3c60753fb8bf356d90702.png" alt="LOVOTに接続するブロック" width="150"/></a><br />
    LOVOTに接続するブロック
</p>

1. ブラウザで[LOVOT STUDY](https://play.lovot.life/)（[https://play.lovot.life/](https://play.lovot.life/)）を開き，「ファイル」メニューから「コンピューターから読み込む」を選択して`sb3`ファイルを読み込みます。
1. 「○○ につなぐ」ブロックで自分の LOVOT の名前が表示されるように選択します。
1. 「ファイル」メニューから「コンピューターに保存する」を選択してファイルを保存します。このとき，ダウンロードしたファイルに上書きしても良いです。

---

## らぼタイマー（[`lovotimer.sb3`](https://github.com/3110/lovot-study/raw/main/lovotimer.sb3)）

30 秒単位（30 秒，60 秒，90 秒，……）で秒数を設定すると LOVOT が時間を計ってくれます。設定した時間になるまで声を出して数えてくれて，時間になると喜びます。

<a href="https://gyazo.com/3768fe270d982f4998bac82afb5e9ae8"><img src="https://i.gyazo.com/3768fe270d982f4998bac82afb5e9ae8.png" alt="らぼタイマー画面" width="600"/></a>

### 実行方法

1. [`lovotimer.sb3`](https://github.com/3110/lovot-study/raw/main/lovotimer.sb3)（[https://github.com/3110/lovot-study/raw/main/lovotimer.sb3]()）をダウンロードして保存します。
1. ブラウザから[LOVOT STUDY](https://play.lovot.life/)（[https://play.lovot.life/](https://play.lovot.life/)）を開き，「ファイル」メニューから「コンピューターから読み込む」を選択してダウンロードした`lovotimer.sb3`ファイルを読み込みます。
1. このページの最初にある「共通：LOVOT の名前を設定する」の手順に従って LOVOT の名前を設定します。
1. キーボードの`c`キーを押して LOVOT に接続します（足を出します）。
1. 画面右上にある緑色の旗のアイコンを押してプログラムを実行します。
1. 実行が終了したらキーボードの`d`キーを押して LOVOT との接続を切ります。

### 使いかた

1. らぼタイマーを実行すると，LOVOT のホーンが緑色に光ります。
1. LOVOT の顔を触って計る時間を設定します。1 回触るごとにホーンが 1 回青く光り，計る時間が 30 秒ずつ増えていきます。
1. 時間が設定できたらホーンを触ります。ホーンが黄色に光ったら開始です。1 秒ごとに LOVOT が声を出して教えてくれます。
1. 設定した時間になったら LOVOT が喜びます。

### カスタマイズ

「時間を 30 ずつ変える」ブロックの 30 を別の値に変更すると，設定する時間の間隔を変更することができます。例えば，30 を 10 に変更すると，顔を触るごとに計る時間が 10 秒ずつ増えるようになります。
