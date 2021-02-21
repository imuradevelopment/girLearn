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


コピペ用

```ps1
    #
    git てすと
```

