##学习git和github常用操作

###关联远程仓库
```
git remote add origin https://github.com/swellwu222/git_learn.git
```
###克隆远程仓库
```
git clone https://github.com/swellwu222/git_learn.git
```
###提交文件到本地参考
```
git add .
git commit -m "修改记录"
```

###提交到远程master分支
```
git push -u origin master
```

###查看状态和改动
```
git status
git diff
```

###查看提交历史
```
git log
```
###查看命令记录
```
git reflog
```
###撤销修改
工作区 add-> 暂存区 commit->版本库
####恢复工作区到最近一次add或commit的状态
```
git checkout -- filename
```
####撤销暂存区的修改
```
git reset HEAD filename
```
####撤销版本库的版本，回退版本
```
git reset --hard commit-id
```
###分支
####创建与分支
```
git branch dev
```
####切换分支
```
git checkout dev
```
####创建并切换
```
git checkout -b dev
```
####查看分支
```
git branch
```