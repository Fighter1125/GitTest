工作区 | 版本库 |
:---:|:---:|
   a | 暂存区、分支（master） |  
1. `git init` 创建本地库

2. `git add` 添加到暂存区

3. `git commit -m "提交信息"` 提交到当前分支

3. `git diff`  查看文件修改了哪些内容

4. `git status` 查看工作区状态

5. `git log` 查看提交历史记录

6. `git reset --hard HEAD^` 回退到上一个版本, `--hard`

7. `git reset --hard id`  回退到指定版本号

8. `git reflog` 查看命令历史 ，当回退错误时，想要恢复，可以用此命令查看版本号id,然后再恢复

9. `git checkout  -- <file>` 撤销修改






