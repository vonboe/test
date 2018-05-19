

初始化工程
```
git init 
```
增加指定文件
```
git add README.md
git add .

```

提交到本地仓库 
```

git commit -m "change test content"

找到工程目录的.git文件夹，打开之后找到config文件，在最后边加上一句话
［user］
 email＝your email
 name＝your name
your email 和your name随便写上就行

```
关联远程仓库
```
git remote add origin https://github.com/vonboe/test.git

```
提交到github
```
git push -u origin master 

```
