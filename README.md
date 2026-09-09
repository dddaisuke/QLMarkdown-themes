# Kanso for QLMarkdown

目に優しい生成りの紙面に、青緑・藤色・テラコッタを合わせたQLMarkdown用テーマです。macOSの外観に応じてライト／ダークを自動で切り替えます。

## 適用方法

1. QLMarkdownを起動します。
2. 「Theme」メニューを `option` キーを押しながら開きます。
3. 「Import a CSS file into the standard themes folder」を選び、[`kanso.css`](./kanso.css) を指定します。
4. Themeで `kanso` を選び、`command + S` で設定を保存します。

反映されない場合はプレビューを更新するか、QLMarkdownを一度終了して起動し直してください。

## 対応範囲

- ライト／ダーク外観
- 見出し、リンク、リスト、引用、表、キーボード表示
- インラインコード、コードブロック、シンタックスハイライト
- ハイライト（`==text==`）とタスクリスト

QLMarkdown 1.5.2の、標準テーマへ追加するカスタムCSS形式に合わせています。

# QLMarkdown のインストール

1. brew install --cask qlmarkdown
2. QLMarkdown.app を開き権限まわりの設定をする
