工作区 | 版本库 |
:---:|:---:|
   a | 暂存区、主分支（master） |  
   
1. `git init` 创建本地库

2. `git add` 添加到暂存区

3. `git commit -m "提交信息"` 提交到当前分支

4. `git diff`  查看文件修改了哪些内容

5. `git status` 查看工作区状态

6. `git log` 查看提交历史记录
---

> ### 回退版本

1. `git reset --hard HEAD^` 回退到上一个版本, `--hard`

2. `git reset --hard id`  回退到指定版本号

3. `git reflog` 查看命令历史 ，当回退错误时，想要恢复，可以用此命令查看版本号id,然后再恢复

---
> ### 撤销修改

1. `git checkout  -- <file>` 撤销修改

2. `git reset HEAD <file>` 撤销暂存区的修改，回退到工作区

---
> ### 删除文件

1. `git rm <file>` 如果要从版本库删除，则 `rm` 后还需要 `commit`

2. 如果删错了，则可以使用`checkout -- <file>` 从版本库中还原

---
> ### 添加远程库

1. `git remote add origin 仓库地址`  关联远程库

2. `git push -u origin master`  push到远程库

3. `git clone 仓库地址`  克隆远程库

---
> ### 分支管理

1. `git branch dev` 创建dev分支

2. `git checkout dev` 切换到dev分支
 
3. `git checkout -b dev`  创建并切换到dev分支

4. `git branch` 查看当前分支

5. `git merge dev` 合并dev分支到当前分支

6. `git branch -d dev` 删除dev分支 

fsdfdfdsa