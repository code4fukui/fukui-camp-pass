# fukui-camp-pass

福井県のキャンプ場や観光スポットを検索・閲覧できるウェブアプリケーションです。

## デモ
https://takameron-fukui-camp-pass.deno.dev

## 機能
- 福井県の地図上にキャンプ場や観光スポットを表示
- 施設の詳細情報の確認
- 福井県の市町村名クイズ

## 必要環境
- Deno 1.24.0以上

## 使い方
1. リポジトリをクローンする
```
git clone https://github.com/your-username/fukui-camp-pass.git
```
2. プロジェクトディレクトリに移動
```
cd fukui-camp-pass
```
3. サーバーを起動
```
deno task start
```
4. ブラウザで `http://localhost:8000` にアクセス

## データ・API
- キャンプ場や観光スポットの情報は `assets/data/camp.csv` から取得
- 市町村名クイズデータは `quiz.ts` から生成

## ライセンス
MIT License