# **github操作手順**
## 1.gitを使う宣言をする
`git init`

## 2.gitの管理対象に追加
`git add 管理対象にしたいもの`
`git add . 現在のディレクトリ以下を対象に追加`
## 3.対象に変更を反映
`git Commit ローカルリポジトリに反映"コメント"``
`git Push リモートリポジトリに反映`
## 4.共有リポジトリを登録
`git remote add origin https://github.com/xxx/xxx.git`
## 5.共有リポジトリに反映
`git push -u origin master`

# 変更後ファイルをpushするまで
### ・上記の手順2から繰り返す（４は必要なし）

# ・その他
## ・リポジトリのクローン作成
作業を始めるために、リポジトリをローカルにクローン（コピー)する
`git clone リポジトリのURL.git`
## ・ブランチを切る
`git checkout -b　ブランチ名`
## ・ファイルの状態を確認
`git status`
