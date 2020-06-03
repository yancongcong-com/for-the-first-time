# Git

### Git基础命令

Git初始化

```linux
git  init
```

Git的文件状态

```
git   status
```

Git把文件添加到暂存区

```
git   add  .
```

Git把文件提交到版本库

```
git  commit   -m  '版本说明'
```

Git查看版本库

```
git   log
```

Git回滚到以前版本

```
git  reset --hard  版本号
```

Git回滚到之后版本

```
git  reflog
git  reset  --hard  版本号
```

Git分支

查看

```
$ git branch
```

创建

```
$ git branch qq
```

切换

```
$ git checkout qq
```

合并

```
$ git  merge qq
```

删除

```
$ git branch -d qq
```

## GitHu

推送

```
$ git remote add origin https://github.com/yancongcong-com/for-the-first-time.git
$ git push -u origin master
```

下载

```
$ git clone    https://github.com/yancongcong-com/for-the-first-time.git
```

更新

```
git  pull origin  dev
```

合并

```
$ git rebase -i HEA~3
```

变基

```
$ git rebase 分支
$ git checkout master
$ git merge qq
```

分叉

```
$ git fetch origin qq
$ git rebase origin/qq
```

## 快速对比

安装beyond compare

配置beyond compare

```.
git  config --local merge.tool bc3
git  config --local mergetool.path '路径'
git  config --local mergetool.keepBackup false
```

启动beyond compare

```
git  mergetool
```

D:\beycond_Compare\Beyond Compare 4