# -知识点总结

1. git
git clone + SSH

git status 查看状态

git checkout branch名字 切换分支

git add 开始跟踪一个文件

git rm 删除文件

git log 

git diff 改动的区别

git commit --amend 覆盖上次的提交

git fetch 与pull的区别是fetch不会合并改变

git branch -d  删除本地branch        git push origin :branch名字 删除远程分支

git stash apply:恢复后，stash内容并不删除;  git stash pop:恢复的同时把stash内容也删了

rebase

 git fetch --all 下拉所有的代码

 git rebase  origin/feature/stage2.2 与远端的branch保持一致

git push origin HEAD 这样就能拉到新更新的stage2.2的代码啦

慎用git push origin HEAD -f 覆盖冲突。。。

昨天用到的命令

git pull 下拉代码

git checkout -b bugfix/ONES-2813954

git stash 暂存改变

git add . 添加修改

git commit -m "说明" 

git push origin HEAD

然后create pull request 添加reviewer
