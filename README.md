# proGit 抜粋

## よく使うコマンド

## 初期設定

```ps1
    # 現在の設定一覧
    git config --list
```

## 作業ツリーとリモート(クローン)

```ps1
    # mylibgitはローカルフォルダ名
    git clone https://github.com/libgit2/libgit2 mylibgit
```

## 作業ツリーとリモート(init)

```ps1
    # 作業ツリーの作成
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin git@github.com:imuradevelopment/test.git
    git push -u origin main
```

# stash(一時保存)

```ps1
    # stash(-uはuntrackedのファイルも退避する)
    git stash save "一時保存" -u
    # stashの一覧
    git stash list
    # stashから呼び出し
    git stash apply stash@{0}
    # stashを削除
    git stash drop stash@{0}
```

コピペ用

```ps1
    #
    git てすと
```
