# git-test

### 设置本地用户名，邮箱
```
git config --global user.name "Your Name"
git config --global user.email you@example.com
```


### 将更改之后的内容提交到远程，若远程版本已经更新则需要先，pull远程版本跟本地版本进行合并之后再重新提交
```
git add file_a 
git commit -m "add filea"
git push  -u origin  master
```


#### 拉取远程，若能auto merger则直接会生成一个auto merger 的commit，若不能的话需要，git diff 查看冲突，再解决冲突，之后再提交
```
git pull

optional:fixed the conflict
git diff
```

### 将本地分支推送到远程创建一个远程分支
```
git checkout -b dev
git push origin dev
```

### 删除远程分支:表示删除
```
git push origin :dev
```


