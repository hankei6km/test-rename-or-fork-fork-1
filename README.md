# test-rename-or-fork-fork
リポジトリ名のリネームとフォークの違いを試す。~これはフォークした~
自分のリポジトリはフォークできない。

GitHub で空のリポジトリを作成し、プッシュしなおした。
 ```
$ git remote set-url origin git@github.com:hankei6km/test-rename-or-fork-fork-1.git
$ git push origin
```

元のリポジトリ: https://github.com/hankei6km/test-rename-or-fork-fork

良いところ 
 
- 元nのリポジトリが残る(どこで分岐したが、手がかり的なものは残る)
 
良くないところ 
 
- 変更したということが確認できない(たぶん) 
- コミット以外は引き継がれない
