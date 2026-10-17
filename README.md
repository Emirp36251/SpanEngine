# Span Engine

C++ と DirectX 12 のための、データ指向のゲームエンジン。
エディタで組み立てて、C++ で書いて、そのまま製品にします。

- サイト (マニュアルとスクリプトガイド): https://emirp36251.github.io/SpanEngine/
- ダウンロード: [Releases](https://github.com/Emirp36251/SpanEngine/releases/latest)
- 不具合の報告と質問: [Issues](https://github.com/Emirp36251/SpanEngine/issues)

> 現在は 0.1 のプレビューです。プロジェクトやシーンの形式、スクリプトの API は、今後変わることがあります。

## 特徴

- **Editor First**: すべての機能を、エディタの画面から操作できます。
- **Data Oriented**: アーキタイプとチャンクに、SoA でデータを並べる ECS。
- **Native Performance**: C++20 と DirectX 12。ガベージコレクションはありません。
- スクリプトも C++ です。エディタを閉じずに、ビルドして読み込み直せます。
- Build で、遊ぶ人の PC に何も入れなくても動く、単体のゲームを書き出せます。

## 動作環境

- Windows 10 または 11 (64 ビット)
- DirectX 12 に対応した GPU
- C++ のスクリプトを書くとき: Visual Studio 2022 か Build Tools の「C++ によるデスクトップ開発」

## インストール

[Releases](https://github.com/Emirp36251/SpanEngine/releases/latest) から、次のどちらかを入手します。

| ファイル | 内容 |
|---|---|
| `SpanEngine-<バージョン>-Setup.exe` | インストーラー。管理者権限は要りません |
| `SpanEngine-<バージョン>-win64.zip` | 展開して、`SpanEditor.exe` を起動します |

`SHA256SUMS.txt` で、ファイルが配布したものと同じかを、確かめられます。

実行ファイルには、まだコード署名をしていません。初回の起動で「Windows によって PC が保護されました」と出たときは、「詳細情報」から「実行」を選んでください。

## ライセンス

無料で使えます。作ったゲームは、商用でも配れます。
エンジン本体の再配布、改変、リバースエンジニアリングはできません。
全文は、インストーラーと zip に含まれる `LICENSE.txt` を読んでください。

このリポジトリには、ソースコードは含まれません。
