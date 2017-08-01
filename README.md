# myxQuizHex

## 概要
2017年8月19日開催のクイズ大会「STU XVIII」で行う団体戦用の得点表示プログラムです。

## インストール・起動方法
### パッケージを利用する場合
1. 右記のファイルをダウンロードする。
    [myxQuizHex-win32-x64.zip](https://drive.google.com/open?id=0B00MyT_-RKCUVWk4SUxlMWlXYzA)
1. ダウンロードしたファイルを適当な場所に展開する。
1. 'myxQuiz.exe'を実行する。

### リポジトリを利用する場合
1. Node.jsのインストール、及び Electron ver.1.4.1 の開発環境を導入する。
1. 右記のディレクトリをcloneする。[miyax0227/myxQuizHex](https://github.com/miyax0227/myxQuizHex)
1. リポジトリの最上位ディレクトリに移動する。
1. 不足しているディレクトリ（`/current/history`, `/twitter/backup`)を作成するため、下記コマンドを実行する。
```shell
clean.js
```
ファイルロックによりエラーが発生する場合は、エラーが発生しなくなるまで繰り返す。
1. Electronコマンドによりmain.jsを読み込む。
```shell
electron .
```

## 使い方

## カスタマイズ方法

## 作成者
Ryoh MIYAMOTO (Miyax)  
[Github](https://github.com/miyax0227)  
[Twitter](https://twitter.com/mi_yax)  

