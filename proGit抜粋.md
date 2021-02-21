# proGit 抜粋

## よく使うコマンド

設定確認

```ps1
    git config --list
```

クローン

```ps1
    # mylibgitはローカルフォルダ名
    git clone https://github.com/libgit2/libgit2 mylibgit
```

変更の一時保存(stash)

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

