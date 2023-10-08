## zipsearch_sample: JS版郵便番号検索

このリポジトリは、JavaScriptベースの郵便番号検索のサンプルコードを提供しています。使用している郵便番号データは、`KEN_ALL_MINI`としてAHREFで配布されています。

配布URL: [https://www.ahref.org/](https://www.ahref.org/)

### セットアップ

#### 1. 郵便番号CSVのダウンロード

最新の郵便番号CSV (`KEN_ALL_MINI.CSV`) を以下のURLからダウンロードしてください。

[https://www.ahref.org/zipcode.php](https://www.ahref.org/zipcode.php)


ダウンロードしたCSVファイルは、サンプルHTMLと同じディレクトリや任意の場所にアップロードしてください。

#### 2. HTMLの組み込み

`public_html` ディレクトリにサンプルHTMLが含まれています。これを参考にして、郵便番号検索機能を自分のサイトやアプリケーションに組み込むことができます。

### 開発環境のセットアップ

Dockerを使用して簡単に開発環境をセットアップすることができます。

```bash
docker-compose up -d
```

立ち上げた後、以下のURLにアクセスして、サンプルページを確認することができます。

- サンプル1: [http://localhost:8080/sample_1.html](http://localhost:8080/sample_1.html)
- サンプル2: [http://localhost:8080/sample_2.html](http://localhost:8080/sample_2.html)
- サンプル3: [http://localhost:8080/sample_3.html](http://localhost:8080/sample_3.html)


