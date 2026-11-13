## Step 2　履歴からコミットを見つける

`git blame` や GitHub の **Blame** を使うと、ファイルの各行を最後に変更したコミットや作成者が分かります。SHA はコミットを識別する値です。

1. **Code** で `docs/_sidebar.md` を開き、**Blame** を選びます。
2. `add sidebar to documentation` のコミットを開き、40桁の SHA の先頭7文字をコピーします。
3. Issue #2 **Fix the sidebar** にコピーした SHA をコメントします。20秒ほど待って案内ページを再読み込みします。

### 画面での確認

- **Code** のファイル一覧から `docs` → `_sidebar.md` を開きます。ファイル表示の上部の **Blame** を選びます。
- コミット画面の識別子をコピーし、**Issues** → **Fix the sidebar**（`#2`）の下部のコメント欄に入力します。コミット名ではなく SHA の先頭7文字を入力します。

[原文](https://github.com/skills/connect-the-dots/blob/main/.github/steps/2-find-commit-in-history.md)
