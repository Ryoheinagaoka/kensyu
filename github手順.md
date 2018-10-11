# **github操作手順**
## ・gitを使う宣言をする
`git init`

## ・ユーザー名・アドレスの入力
## ・ファイルの状態を確認
`git status`
## ・gitの管理対象に追加
`git add 管理対象にしたいもの`
`git add . 現在のディレクトリ以下を対象に追加`
## ・対象に変更を反映
`git Commit ローカルリポジトリに反映"コメント"``
`git Push リモートリポジトリに反映`
## ・共有リポジトリを登録
`git remote add origin https://github.com/xxx/xxx.git`
## ・共有リポジトリに反映
`git push -u origin master`
## ・ユーザー名・アドレスの入力
## リポジトリのクローン作成
作業を始めるために、リポジトリをローカルにクローン（コピー)する
`git clone リポジトリのURL.git`
## ・ブランチを切る
`git checkout -b　ブランチ名`
