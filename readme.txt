git is a  distributed 1  version control system
git is free software under the GPL
git has a mutable index stage.
git tracks changes of files.


git init 初始化该文件夹
cd .git 进入GIT隐藏文件
cd ../   退出隐藏文件
git add readme.txt 添加文件
git commit -m 确认添加
git status 查看git处于什么状态
git diff readme.txt 查看和上一次提交的文件的差别
git log 查看版本
git log --pretty=oneline 查看版本用一行的形式
git checkout -- readme.txt  撤销保存进暂存区
git reset HEAD readme.txt   撤销保存进master 然后用checkout 撤销保存进暂存区。
先在git里创一个存储库
git remote add origin https://github.com/a1237877/learn_git.git
git push -u origin master  这两步为保存进master