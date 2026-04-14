# 0330 — Portfolio Site

イラストレーター・Vtuber **0330** のポートフォリオサイトです。

## 🌐 公開方法（GitHub Pages）

### 手順

1. **このリポジトリを作成**
   ```
   リポジトリ名: 0330-portfolio  （または任意の名前）
   公開設定: Public
   ```

2. **`index.html` をアップロード**
   - GitHub の画面から「Add file → Upload files」で `index.html` をドラッグ＆ドロップ
   - または Git でプッシュ

3. **GitHub Pages を有効化**
   - リポジトリの `Settings` → `Pages`
   - Source: `Deploy from a branch`
   - Branch: `main` / `(root)`
   - `Save` をクリック

4. **数分後に公開される**
   ```
   https://<GitHubユーザー名>.github.io/<リポジトリ名>/
   ```

---

## 📁 ファイル構成

```
/
└── index.html   ← サイト本体（これ1ファイルだけでOK）
```

## ✏️ カスタマイズ

| 内容 | 場所 |
|------|------|
| 自己紹介文 | `#about` セクション |
| SNS リンク | `href="https://x.com/..."` の部分 |
| 実績ツイート | `blockquote` の URL |
| カラー | CSS の `:root` 変数 `--sky` など |

## 🔗 関連リンク

- X (Twitter): [@0330_0m](https://x.com/0330_0m)
- ツイキャス: [twitcasting.tv/0330_0m](https://twitcasting.tv/0330_0m)
