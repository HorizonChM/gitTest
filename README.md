# gitTest，纯粹是为了学习Git的操作和使用
学习git的使用

 - git init 初始化一个仓库
 - git clone 克隆远程仓库到本地
 - git add 当修改了文件之后，将修改的文件进行跟踪
 - git commit 将修改的文件添加到本地版本库
 - git checkout 切换分支
 - git pull 从远程仓库拉取对应的版本，更新到本地
    用法`git pull <远程主机名> <远程分支名>:<本地分支名>`
    例如`git pull origin master:addTitle`
    就表示从远程的master分支拉取到本地的addTitle分支
 - git push 将本地版本更新到远程连接分支
 - git status 查看当前的状态
 - git branch 查看分支
 - git merge 合并分支
 - git push 将本地的分支内容推到远程分支
    用法`git push <远程主机名> <本地分支名>:<远程分支名>`
    例如`git push origin addTitle:addTitle`
    就是将本地的addTitle分支push到远程主机origin的addTitle分支上了
 - last modified by master
 - git reset --hard 3dadf8ka32 强行恢复到某个版本

Notice:
 - git pull 拉取的只是在origin上的本地分支，而不是master分支！！！这点一定要注意，以后应该这样用`git pull origin/master`
    而不是简单的`git pull`... 
