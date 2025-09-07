# ジム検索アプリ - プライバシーポリシー

このリポジトリはジム検索アプリのプライバシーポリシーページを含んでいます。

## GitHub Pagesへのデプロイ手順

### 1. GitHubリポジトリの作成

1. [GitHub](https://github.com)にログイン
2. 新しいリポジトリを作成（例：`mobile-gym-app-privacy-policy`）
3. パブリックリポジトリとして作成（GitHub Pagesの無料版に必要）

### 2. ローカルリポジトリをGitHubにプッシュ

```bash
# GitHubリポジトリのURLを追加（YOUR_USERNAMEを実際のGitHubユーザー名に置き換え）
git remote add origin https://github.com/YOUR_USERNAME/mobile-gym-app-privacy-policy.git

# メインブランチをプッシュ
git branch -M main
git push -u origin main
```

### 3. GitHub Pagesの設定

1. GitHubのリポジトリページで「Settings」タブをクリック
2. 左サイドバーで「Pages」をクリック
3. 「Source」セクションで以下を選択：
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
4. 「Save」をクリック

### 4. デプロイの確認

- 数分後、以下のURLでプライバシーポリシーページが公開されます：
  `https://YOUR_USERNAME.github.io/mobile-gym-app-privacy-policy/`

## ファイル構成

- `index.html` - プライバシーポリシーのメインページ
- `README.md` - このファイル（デプロイ手順の説明）

## 更新方法

プライバシーポリシーを更新する場合：

1. `index.html`を編集
2. 変更をコミット：
   ```bash
   git add index.html
   git commit -m "プライバシーポリシーを更新"
   git push origin main
   ```
3. GitHub Pagesが自動的に更新されます（通常数分で反映）

## 注意事項

- GitHub Pagesは静的サイトのみサポート
- 変更がサイトに反映されるまで最大10分程度かかる場合があります
- カスタムドメインを使用する場合は、GitHub Pagesの設定でドメインを追加できます
