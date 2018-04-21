Updates were rejected because a pushed branch tip is behind its remote
```

把指定的文件夹推到 指定的分支

分支test上有一个文件A，你在test1分支上， 此时如果想用test分支上的A文件替换test1分支上的文件的话，可以使用git checkout test1, 然后git checkout test -- A
```