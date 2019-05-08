# Git命令行操作

## 本地操作

初始化仓库 `git init`

添加文件到暂存区 `git add <file>`

提交文件到仓库 `git commit -m <message>`

查看工作去状态 `git status`

查看修改内容 `git diff`

回退版本 `git reset --hard commit_id`

查看提交历史 `git log`

查看命令历史 `git reflog`

工作区 暂存区 版本库

![工作区-暂存区版本库](C:\Users\maybe\Desktop\git_test\学习\工作区-暂存区版本库.jpg)

回退工作区文件 `git checkout -- file`

回退暂存区文件 `git reset HEAD <file>`

删除文件 `git rm`

## 远程仓库

关联远程库 `git remote add origin git@server-name:path/repo-name.git`

第一次将master 推送到远程库 `git push -u origin master`

推送最新修改 `git push origin master`

克隆远程仓库 `git clone`

## 分支管理

查看分支：`git branch`

创建分支：`git branch <name>`

切换分支：`git checkout <name>`

创建+切换分支：`git checkout -b <name>`

合并某分支到当前分支：`git merge <name>`

删除分支：`git branch -d <name>`

![分支管理](C:\Users\maybe\Desktop\git_test\学习\分支管理.jpg)

查看分支合并图`git log --graph`

团队分支示意图

![团队分支](C:\Users\maybe\Desktop\git_test\学习\团队分支.jpg)

把本地未push的分叉提交历史整理成直线 `git rebase`