# CHIRIMEN OS イメージの焼き方

## CHIRIMEN の OS イメージについて

- CHIRIMEN の OS イメージは、 Rasbian OS をカスタマイズしたもので、下記の２種類があります。
- URL 又は、QR コードから OS イメージをダウンロードして下さい。

### CHIRIMEN for Raspberry Pi

- Raspberry Pi 3B+, 4B 用(32bit)
- https://github.com/chirimen-oh/chirimen/releases/tag/20210812

  <img src="images/CHIRIMEN-for-Pi-Over-3B.png" width="100">

### CHIRIMEN for Raspberry Pi Zero

- Raspberry Pi Zero 用(32bit)
- https://github.com/chirimen-oh/chirimen-lite/releases/tag/v1.2.0

  <img src="images/CHIRIMEN-for-Pi-Zero.png" width="100">

### Raspberry Pi 3B+, 4B 用(32bit) ダウンロード

1. https://github.com/chirimen-oh/chirimen へ行きます。<br>
   <img src="images/repo-Pi-01.png" width="300">

2. Releases をクリックします。<br>
   <img src="images/repo-Pi-02.png" width="300">

### Raspberry Pi Zero 用(32bit) ダウンロード

1. https://github.com/chirimen-oh/chirimen-lite へ行きます。<br>
   <img src="images/repo-Pi-Zero-01.png" width="300">

2. Releases をクリックします。<br>
   <img src="images/repo-Pi-Zero-02.png" width="300">

## CHIRIMEN の OS を SD カードに焼く

- Raspberry Pi Zero 用(32bit) を例に手順を解説します。
- mac OS と [balena Etcher](https://www.balena.io/etcher) を使った例です。
- ※ ご使用の OS やライティングソフトにあったものをお使い下さい

1. SD カードを初期化します。<br>
   <img src="images/image-write-000.png" width="300">
2. zip を解凍／展開します。<br>
   <img src="images/image-write-001.png" width="300">
3. [balena Etcher](https://www.balena.io/etcher) を起動し、上記イメージを選択します。<br>
   <img src="images/image-write-002.png" width="300">
4. SD カードを選択します。<br>
   <img src="images/image-write-003.png" width="300">
5. Flash ボタンをクリックし、書き込みを開始します。<br>
   <img src="images/image-write-004.png" width="300">
6. OS のパスワードを入力します。<br>
   <img src="images/image-write-005.png" width="300">
7. イメージを書き込み中です。<br>
   <img src="images/image-write-006.png" width="300">
8. 書き込みが完了しました。<br>
   <img src="images/image-write-007.png" width="300">

## CHIRIMEN の OS を 使う

- この手順で作成した SD カードをそれぞれの Raspberry Pi ボートに装着して起動して下さい。
- CHIRIMEN for Raspberry Pi
  - Raspberry Pi 3B+, 4B 用(32bit)
- CHIRIMEN for Raspberry Pi Zero
  - Raspberry Pi Zero 用(32bit)
