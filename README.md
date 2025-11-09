# 🍱 Panasonic Lunch Navi（パナラン）

社内のランチ情報を共有するWebアプリケーション

## 📋 プロジェクト概要

Panasonic社員向けのランチ情報共有アプリです。外部のランチ店情報を社内で共有し、社員同士の情報交換を促進します。

## 🚀 セットアップ

### 必要な環境

- Python 3.8以上
- Streamlit

### インストール

1. リポジトリをクローン
```bash
git clone <repository-url>
cd 20251109_PanaLaunchNavi
```

2. 依存パッケージをインストール
```bash
pip install -r requirements.txt
```

3. アプリを起動
```bash
streamlit run app.py
```

4. ブラウザで `http://localhost:8501` を開く

## 📁 プロジェクト構造

```
20251109_PanaLaunchNavi/
├── app.py                 # メインアプリケーション
├── stores.json            # 店舗データ
├── requirements.txt       # Pythonパッケージ一覧
├── plan.md               # 開発計画・進捗管理
├── README.md             # プロジェクト説明
└── docs/                 # ドキュメント
    ├── project_v2.md     # 企画書
    └── project_specifications.md  # 仕様書
```

## 🎯 機能

- 店舗リスト表示
- 店舗詳細表示
- 新規店舗投稿
- 検索・フィルター機能
- 評価・コメント機能

## 📚 ドキュメント

詳細なドキュメントは `docs/` フォルダーを参照してください。

- 企画書: `docs/project_v2.md`
- 仕様書: `docs/project_specifications.md`
- 開発計画: `plan.md`

## 👥 開発チーム

ゆんチーム（開発者2名）

## 📝 ライセンス

社内利用のみ

---

**Panasonic Lunch Navi** - 社員同士の情報が温かく循環するランチ紹介アプリ

