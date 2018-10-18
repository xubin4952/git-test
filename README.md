# git-test

### config your name and email
```
git config --global user.name "Your Name"
git config --global user.email you@example.com
```


### 将更改之后的内容提交到远程
```
git add file_a 
git commit -m "add filea"
git push  -u origin  master
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
