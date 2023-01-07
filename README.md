# アプリ名

## Fany

## コンセプト

- 近くの良さげな飲食店がすぐに見つかる
- ここら辺でどっか美味しい店ない？を解決

### こだわったポイント

すぐにお店に向かえるように、詳細画面から Google Map でルート案内を開始

### デザイン面でこだわったポイント

### 公開したアプリの URL（Store にリリースしている場合）

https://fany-fuku.azurewebsites.net

### 該当プロジェクトのリポジトリ URL（GitHub,GitLab など Git ホスティングサービスを利用されている場合）

https://github.com/a2c6201/Fany

# 開発環境

## 開発環境

virtualenv 20.17.0

## 開発言語

Python 3.10.8

## フレームワーク(ver.含む)

Flask 2.2.2

## テーブル定義(ER 図)などの設計ドキュメント

## 動作対象端末・OS

## 動作対象 OS

## 開発期間

# アプリケーション機能

## 機能一覧

- レストラン検索：ホットペッパーグルメサーチ API を使用して、現在地周辺の飲食店を検索する。
- レストラン情報取得：ホットペッパーグルメサーチ API を使用して、飲食店の詳細情報を取得する。
  <!-- - 電話アプリ連携：飲食店の電話番号を電話アプリに連携する。 -->
  <!-- - 地図アプリ連携：飲食店の所在地を地図アプリに連携する。 -->

## 画面一覧

- 検索画面 ：条件を指定してレストランを検索する。
- 一覧画面 ：検索結果の飲食店を一覧表示する。
- 詳細画面 : 検索結果画面で選択した店舗の情報を表示する。

## 使用している API,SDK,ライブラリなど

- ホットペッパーグルメサーチ API
- Geolocation API

###　 Lint tool

- flake8 (CI ツールで利用)
- autopep8

## いただきたいアドバイス

## 使用方法

.env ファイルを作成し、API key をそれぞれ追加(.env.sample を参照)

```
HOT_PEPPER_API_KEY = 'Hot Pepper API key'
GEOCODING_API_KEY = 'Geocoding API key'
```

ターミナルで以下コマンドを入力し、使用ライブラリをインストール

```
pip install -r requirements.txt
```
