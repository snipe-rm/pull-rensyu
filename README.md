# pull-rensyu

# サイトのbaceのコンテンツの作成手順
  - contentsの中身を各自作成する
  - お勧め情報を１つの contentsの中に作成する

## 他の人とやる時の大まかな流れ
  1. Github上のレポジトリからローカルにclone(保存)する。
  2. Pull Request用のBranchを作成する
    - 左下の「main」をクリック
    - 「新しいブランチの作成＋」でブランチ作成
  3. クローンしたディレクトリの編集
  4. ローカルでadd⇒commit、Githubへpushする
    - 編集したファイルをステージング
    - メッセージを入力し、コミットしてプッシュ
  5. Github上でPullRequestする
    - 右上の緑色のCompare & pull requestボタンをクリック
    - どういった変更を加えたのかを説明する内容を記入
    - どのブランチからどのブランチにpull requestするかを確認する
      ※developブランチからmasterブランチへのpull request
  6. 「Create pull request」ボタンを押して、Pull Requestを作成
  7. Github上でMergeする
    - ※この作業は、本来、自分以外のレポジトリ管理者がコードを確認して実行される
    - 左下の緑色の[Merge pull request]ボタンを押して、Mergeを実行する
  8. 確認
    - うまく合体できていれば成功！確認

## 自分一人で二役やってブランチ練習する方法
  1. ブランチ作成
  2. ブランチの発行ボタン（vscode）
  3. vscodeで編集
  4. コミットしてプッシュ
  5. リモート(github）で プルリクエスト → これは私かな？
  6. リモート(github）で Margeしてプルリクエスト → これも私かな？
  7. ローカル（vscode）⌘＋shift+Pで「Git：チェックアウト先（main選択）」
  8. ローカル（vscode）「Git:ブランチをマージ（ブランチを選択）」