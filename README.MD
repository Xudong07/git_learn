<center> <font size=6> Git </font> </center>   

## Commands (you can get all commands by running git without any options)  

## git help + command can help much  

- git init
- git add
- git commit -m "description"
- git config 
  - git config --global user.email "you@example.com"
  - git config --global user.name "Your Name"
- git status
- git diff
- git log
  - git log --pretty=oneline
- git rest
  - git rest --hard [HEAD^ HEAD^^ HEAD100^ Commit id]
- git reflog
- git checkout
- git rm
- git clone
- 将本地库和远程库链接
 - git remote add
 - git remote remove
- git branch
- git merge
- git switch
- git stash
- git  cherry-pick
- git remote
- git tag


## Common Sense

- 暂存区(index or stage)
  - git add 会将工作区的东西添加到暂存区，git commit 会提交暂存区的内容
- 工作区
  - 当前工作的目录
- 版本库
  - git commit 会将暂存区的内容添加到版本库
- git track the changes not the file
- -- 代表工作区
- 远程仓库的默认名称为origin
- git test conflict







