
### gitの基本設定
git config --global user.name {sohdacafe}
git config --global user.email {sohdacafe@gmail.com}


### ローカルリポジトリとして初期化
* VSCodeで対象フォルダを開く
* メニューから『ターミナル⇒新しいターミナル』を選択
* ターミナルに実行コマンドを入力、実行。
  git init


### githubのリモートリポジトリ作成
* …or push an existing repository from the command lineのコマンドを記憶しておく
git remote add origin https://github.com/sohdacafe/share_code.git
git branch -M main
git push -u origin main

### GitHubと連携させる
* リモートリポジトリに紐づける
  git remote add origin https://github.com/{ユーザー名}/{リポジトリ名}.git
  git remote add origin https://github.com/{sohdacafe}/{share_code}.git



### GitHub実行コマンド
* ローカルリポジトリとGitHubのリモートリポジトリを紐づける作業
git remote add origin https://github.com/{ユーザー名}/{リポジトリ名}.git
* リモートリポジトリに紐づいたかの確認
git remote -v
以下が出力されればOK
origin  https://github.com/{ユーザー名}/{リポジトリ名}.git (fetch)
origin  https://github.com/{ユーザー名}/{リポジトリ名}.git (push) 
* リモートリポジトリにプッシュ
git branch -M main
git push -u origin main
