推送本地更新到远程
====

+ git add
`git add file`
`git add *`

+ git status
`git status `
查看上次提交后是否有更改

+ git commit
Git 为你的每一个提交都记录你的名字与电子邮箱地址，所以第一步需要配置用户名和邮箱地址。
`git config --global user.name 'name'`
`git config --global user.email name@email.com`
使用 git add 命令将想要快照的内容写入缓存区， 而执行 git commit 将缓存区内容添加到仓库中。
`git commit -m '第一次版本提交'`

+ git push
    `git push origin master`

取得远程更新
====
`git pull`
