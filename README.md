# space-simulator

space-simulator プロジェクトへの貢献、ありがとうございます！

このドキュメントでは、**Webブラウザのみ** を使用してGitHub上で開発を進めるためのフローについて説明します。ローカル環境でのGitコマンドやエディタの操作は不要です。

## 1. イシューの作成

新しい機能の追加、バグの修正、または改善を行う際は、まず **イシュー (Issue)** を作成してください。これは作業内容を明確にし、進捗を追跡するために重要です。

**作成方法:**

1. GitHub リポジトリのページにアクセスします。

2. 上部のナビゲーションバーにある **Issues** タブをクリックします。

3. **New issue** ボタンをクリックします。

4. 適切なテンプレート（バグ報告、機能リクエストなど）を選択し、以下の情報を記述します。

   * **タイトル:** 簡潔で分かりやすいもの（例: `[Feature] 惑星間の重力計算を追加`）
   * **説明:** 目的、背景、期待される動作、再現手順（バグの場合）など
   * **ラベル:** 適切なラベル（`bug`, `enhancement` など）
   * **担当者:** 必要に応じて自身をアサイン

5. **Submit new issue** をクリック

## 2. ブランチの作成

イシューに対応する作業を行うために新しい **ブランチ (Branch)** を作成します。

**作成方法:**

1. 作成したイシューのページを開きます。
2. イシュー説明の下「Development」セクションで **Create a branch** をクリック
3. デフォルトのブランチ名（例: `feature/1-your-issue-title`）を必要に応じて変更（例: `feature/123-add-gravity-calculation`）
4. **Create branch** をクリック

## 3. コードの記述とコミット

GitHub Codespaces（推奨）またはWebエディタを使用します。

### Codespacesの場合

1. **Code** ボタン→ **Codespaces** タブ
2. **Create codespace** をクリック

### Webエディタの場合

* 新しいファイル: **Add file > Create new file**
* 既存ファイル: ファイルを開き、鉛筆アイコンで編集

**コミットメッセージ例:**

```
Feat: Implement basic gravitational force calculation

- 重力計算の追加

Closes #123
```

編集後 **Commit changes** をクリック

## 4. プルリクエスト作成

1. コミット後に表示される **Compare & pull request** をクリック
2. タイトル、説明（`Fixes #<issue number>`）、レビュアーを記入
3. **Create pull request** をクリック

## 5. コードレビューと修正

* プルリクエストページのコメントを確認
* **Files changed** タブで鉛筆アイコンから修正
* 修正後再コミット（PRが自動更新）

## 6. マージ

1. 承認後 **Merge pull request** をクリック
2. **Delete branch** でブランチを削除

---

このWebブラウザ上での開発フローに従うことで、ローカル環境のセットアップなしにプロジェクトへ貢献できます。ご協力ありがとうございます！
