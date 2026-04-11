# font2openscad

文字列をOpenSCADのポリゴンに変換するツールです。TTF/OTFフォントを使用して2D形状を生成できます。

## デモ
https://code4fukui.github.io/font2openscad/

## 機能
- TTF/OTFフォントを読み込み、任意の文字列を2Dポリゴンに変換
- OpenSCADのポリゴン定義コードを出力
- フォントサイズ、文字間隔、曲線精度などのパラメータ調整が可能
- 生成したデータをプレビュー表示

## 必要環境
ウェブブラウザ

## 使い方
1. TTF/OTFフォントを選択または追加
2. 表示したい文字列を入力
3. 各種パラメータを調整
4. 「生成」ボタンをクリックし、出力されたOpenSCADコードをコピー
5. OpenSCADでポリゴンを3D化

## ライセンス
このリポジトリのソースコードは [LICENSE](LICENSE) に記載の MIT License です。

同梱している [`font/Noto_Sans_JP/`](font/Noto_Sans_JP/) 以下のフォントファイルは、ソースコードとは別に SIL Open Font License 1.1 で提供されています。

- フォント名: Noto Sans JP
- 著作権表示: Copyright 2014-2021 Adobe
- ライセンス本文: [`font/Noto_Sans_JP/OFL.txt`](font/Noto_Sans_JP/OFL.txt)
- 同梱README: [`font/Noto_Sans_JP/README.txt`](font/Noto_Sans_JP/README.txt)

このリポジトリをフォント込みで再配布する場合は、上記の OFL ライセンス文書と著作権表示ファイルをフォントファイルとあわせて保持してください。
