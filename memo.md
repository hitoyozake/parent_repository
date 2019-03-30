# subtreeコマンド流れ
```
git remote add XXXX https://....git
git subtree add --prefix=SUB_DIR XXXX [branch]
```

# 親リポジトリへのpush

普通にpushすると親のポジトリにしか反映されない.  　

# 子リポジトリへのpush/pull  

```
git subtree [push/pull] --prefix=XXXX [branch]
```
を用いると子リポジトリの変更内容の取り込み，適用が可能




