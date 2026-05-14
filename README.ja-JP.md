# csp-toolkit

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <a href="README.ja-JP.md">日本語</a>
</p>

自分が開発した Clip Studio Paint 向けツールと、他の開発者によって作られた、自分が見つけた便利そうなまたは興味深いツールをまとめた入口です。

自分が開発した各ツールは、それぞれ独立したリポジトリで管理されています。この repo は、ツールの概要、プレビュー、インストール案内へのリンクをまとめた軽量なインデックスです。あわせて、自分が見つけた便利そうな、または興味深い CSP 関連ツールも少しまとめています。

## ツール一覧

### [GoPieMenu](https://github.com/RyuuMeow/GoPieMenu)

カーソル中心に表示される PieMenu です。大量の Clip Studio Paint ショートカットを 1 つの PieMenu にまとめ、カテゴリ分けや階層メニューとして整理できます。たくさんのショートカットを覚える必要はなく、1 つのホットキーだけでペン先の近くから操作できます。

こんなときに便利です：

- 多数の CSP ツール、アクション、コマンドをわかりやすく分類したい。
- 大規模または専門的な作業フロー向けに階層式ショートカットメニューを作りたい。
- 描画エリアから手を離さず、1 つのホットキーでよく使う操作を呼び出したい。

<p align="center">
  <img src="demo/GoPieMenu_Demo.gif" alt="GoPieMenu demo">
</p>

---

### [ClipStudioPaint-Grayscale-Viewer](https://github.com/RyuuMeow/ClipStudioPaint-Grayscale-Viewer)

Clip Studio Paint の作業を邪魔しないグレースケールプレビュー用オーバーレイツールです。CSP アプリの上に重ねて表示されるため、別のプレビューウィンドウを開く必要がありません。ホットキーだけで Photoshop に近いグレースケールプレビュー体験を得られます。

こんなときに便利です：

- CSP のキャンバスから離れずにグレースケールプレビューを切り替えたい。
- レイヤー、カラー設定、作業ファイルを変更せずに明度関係を確認したい。
- 一時的な色レイヤーを作成したり、塗りつぶしたり、レイヤー表示を何度も切り替えたりせずに明度を確認したい。
- CSP で Photoshop に近いグレースケールプレビューの流れを使いたい。

<p align="center">
  <img src="demo/ClipStudioPaint-Grayscale-Viewer_Demo.gif" alt="ClipStudioPaint-Grayscale-Viewer demo">
</p>

## 見つけた他の CSP ツール

他の作者によって作られた、便利そうなまたは興味深い Clip Studio Paint 関連ツールです。

> これらのプロジェクトは、それぞれの作者によって管理されています。インストール方法、互換性、サポート、ライセンス情報については、各リポジトリの説明を確認してください。

- [ClipStudioPaint-Smooth-Color-Adjustment](https://github.com/MMmmmoko/ClipStudioPaint-Smooth-Color-Adjustment) - CSP の変更やプラグインにより、色調補正やよく使うぼかし機能のプレビュー応答性を改善し、タイムラプス書き出しオプションなどの補助機能も提供するツール。
- [clip_to_psd](https://github.com/dobrokot/clip_to_psd) - Clip Studio Paint の `.clip` ファイルを PSD ファイルに変換する Python スクリプト。
- [CSPBrushExtract](https://github.com/MorrowShore/CSPBrushExtract) - Clip Studio Paint の `.sut` ブラシファイルからパラメータとブラシ先端画像を抽出するツール。
- [Brush-Converter](https://github.com/tohsakrat/Brush-Converter) - Photoshop `.abr`、Procreate `.brushset`、Clip Studio Paint `.sut` などのブラシ形式から素材画像やパラメータを取り出すためのスクリプト。

## はじめに

1. 上の一覧から使いたいツールを選びます。
2. そのツールの専用リポジトリを開きます。
3. 最新リリースをダウンロードし、各プロジェクトのセットアップ手順に従ってください。

各ツールは機能、要件、リリースサイクルが異なるため、詳しいインストール方法と使い方はそれぞれのリポジトリで管理されています。

## リポジトリ構成

```text
csp-toolkit/
├── demo/             # README で使用するプレビュー GIF
├── README.md         # English project index
├── README.zh-TW.md   # 繁體中文說明
├── README.zh-CN.md   # 简体中文说明
└── README.ja-JP.md   # 日本語 README
```

## フィードバック

不具合報告、機能案、ワークフローに関する提案を歓迎します。特定のツールに関する内容は、そのツールのリポジトリで issue を作成してください。議論とコードを同じ場所に保てます。

## ライセンス

リンク先の各ツールは、それぞれ異なるライセンスを使用している場合があります。コードを利用、変更、再配布する前に、各リポジトリのライセンス情報を確認してください。
