<p align="center">
  <img src="https://komarev.com/ghpvc/?username=KrishBharadwaj5678&label=Profile%20Views&color=brightgreen&style=for-the-badge" />
  <img src="https://hits.sh/github.com/KrishBharadwaj5678/Scrapy.svg?style=for-the-badge&label=Repo%20Views&color=blue" />
  <img src="https://img.shields.io/github/stars/KrishBharadwaj5678/Scrapy?style=for-the-badge&color=yellow" />
  <img src="https://img.shields.io/github/last-commit/KrishBharadwaj5678/Scrapy?style=for-the-badge&color=orange" />
  <img src="https://img.shields.io/github/repo-size/KrishBharadwaj5678/Scrapy?style=for-the-badge&color=blue" />
</p>

<p align="center">
  <a href="README.md">English</a> | 
  <a href="README.pt.md">Português</a> | 
  <a href="README.ja.md">日本語</a> | 
  <a href="README.ru.md">Русский</a>
</p>

<h1 align="center"><img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/icons/scrapy.png" width="38"/> Scrapy</h1>

<p align="center">
  Scrapyは、PythonをベースとしたWebスクレイピングプロジェクトです。Webサイトから構造化データを抽出し、MongoDBに効率的に保存します。
</p>

<img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/divider.gif" width="100%"/>

## <img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/features.gif" width="35"/> 機能

| 機能 | 説明 |
| ---- | ---- |
| 🕸️ Webクローリング | Scrapyを使用してWebサイトを効率的にクロール |
| 📦 データ抽出 | Webページから整理されたデータを抽出 |
| 🍃 MongoDBへの保存 | 収集したデータをMongoDBに保存 |
| ⚡ 高速処理 | 非同期リクエストによる効率的なスクレイピング |

<img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/divider.gif" width="100%"/>

## <img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/techStack.gif" width="35"/> 使用技術

| 技術 | 用途 |
| ---- | ---- |
| <img src="https://skillicons.dev/icons?i=python" width="25"/> **Python** | メインのプログラミング言語 |
| <img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/icons/scrapy.png" width="25"/> **Scrapy** | Webクローリング・スクレイピングフレームワーク |
| <img src="https://skillicons.dev/icons?i=mongodb" width="25"/> **MongoDB** | 収集したデータの保存 |
| <img src="https://skillicons.dev/icons?i=mongodb" width="25"/> **PyMongo** | PythonとMongoDBの連携 |

<img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/divider.gif" width="100%"/>

## <img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/gettingStarted.gif" width="35"/> はじめに

### 1️⃣ リポジトリをクローン

```bash
git clone https://github.com/KrishBharadwaj5678/Scrapy.git
```

### 2️⃣ プロジェクトへ移動

```bash
cd Scrapy
```

### 3️⃣ 依存関係をインストール

```bash
pip install -r requirements.txt
```

### 4️⃣ MongoDBを設定

spiders/main.py を開き、MongoDBの接続URIを設定します。

```bash
MONGO_URI = "mongodb_url"
```

"mongodb_url" を実際のMongoDB接続文字列に置き換えてください。

### 5️⃣ MongoDBを起動

MongoDBがローカルで実行されていること、または指定したMongoDB接続URIにアクセスできることを確認してください。

### 6️⃣ フォルダへ移動

```bash
cd spiders
```

### 7️⃣ Spiderを実行

```bash
scrapy crawl main
```

<img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/divider.gif" width="100%"/>

## <img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/license.gif" width="35"/> ライセンス

このプロジェクトは MIT License のもとで公開されています。

詳細については [LICENSE](LICENSE) ファイルをご覧ください。

<p align="center"> 
  <img src="https://github.com/KrishBharadwaj5678/Scrapy/raw/main/assets/readme/footer.gif" width="320px"/> 
</p> 

