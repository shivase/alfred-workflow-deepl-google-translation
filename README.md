# Alfred DeepL & Google Translation workflow

[![download](https://img.shields.io/github/downloads/shivase/alfred-worlflow-deepl-google-translation/total)](https://github.com/shivase/alfred-worlflow-deepl-google-translation/releases)

クリップボード上の英語を日本語にしてブラウザ上に表示する alfred workflow です。
簡易的に作ったものなので不備が多々ありますがご了承ください

Google と DeepL に対応しており、二つの結果を同時に表示させる機能も追加しました

![sample](sample.gif)

## 前提

- alfred 5 & Powerpack(有料)
- DeepL API キー(有料 or 無料)  
  DeepL サイトで API キーを取得しておいて下さい。無料アカウントでも大丈夫ですが、月間の使用文字数に制限が出ます
- Google Translate API キー  
  同様に Google の API キーも取得しておいてください  
  [Google Translate API を使って翻訳ボタンを作る \| JavaScript \| ドキュメント \| a\-blog cms developer](https://developer.a-blogcms.jp/document/javascript/google-translate-api.html)
- jq & nkf  
  homebrew などでインストールしておいて下さい

## インストール手順

### ダウンロード

[release](https://github.com/shivase/alfred-worlflow-deepl-google-translation/releases)より DeepL-Google-Translator.alfredworkflow をダウンロードし、alfred にインストールして下さい

### API キーの登録

ワークフロー登録後、以下のような画面が出力されますので、記載に従ってAPIキーなどをいれて下さい

![install1](install_image1.png)

途中でAPIキーなどを変えたい場合は、ワークフロー画面の左上に`Configure Workflow`というのがあるので、そこをクリックして下さい

![install2](install_image2.png)

### Hotkey の登録

3 種類のホットキーを設定できるので、お好みでホットキーを設定して下さい

- DeepL のみ
- Google のみ
- DeepL + Google 同時

## 使い方

クリップボードの値をそのまま変換するので、変換したい文字を選択してクリップボードにコピーし、決めたホットキーを押すだけです。あとは自動的にブラウザが開きます

## やりたいこと・やること

- JA -> EN 変換

## Thanks

html 部分は以下を参考にしています

[【ご紹介】iPad で英論文を爆速超快適に読めるように \.\.\. \- Qiitahttps://qiita\.com › iPad](https://qiita.com/hiro2do/items/43fb123769cd9bb82476)
