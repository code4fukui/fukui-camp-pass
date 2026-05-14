# fukui-camp-pass

クイズ形式の体験を通じて、福井県の様々な市町村について探索し、学ぶことができるWebアプリケーションです。

## デモ
アプリケーションは以下にデプロイされています: https://takameron-fukui-camp-pass.deno.dev

## 機能
- 福井県のインタラクティブな地図
- 市町村に関するユーザーの知識を試すクイズ形式の質問
- 質問の順序と選択肢のランダム化
- 正解・不正解の即時フィードバック
- クイズの再挑戦オプション

## 要件
このプロジェクトは、JavaScriptおよびTypeScript向けのモダンでセキュアかつ高速なランタイムであるDenoを使用して構築されています。プロジェクトを実行するには、システムにDenoをインストールする必要があります。

## 使い方
1. リポジトリをクローンします:
```
git clone https://github.com/your-username/fukui-camp-pass.git
```
2. プロジェクトディレクトリに移動します:
```
cd fukui-camp-pass
```
3. サーバーを起動します:
```
deno run --allow-net --allow-read --watch serve.ts
```
4. Webブラウザを開き、`http://localhost:8000` にアクセスしてアプリケーションを利用します。

## データ / API
本アプリケーションは、ローカルのデータファイルを使用してクイズの質問を生成し、地図を表示します。データファイルは `assets/data` ディレクトリに配置されています。

## ライセンス
MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
