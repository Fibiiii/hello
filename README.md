# hello
# 基本操作
# git add -> git commit -m ->git push (origin)
# git commit 一定要加 -m""
# git log --pretty=shot (只显示提交信息第一行)
# git log (+文件名就显示该文件相关的日志)（+目录名就显示该目录下的日志）（-p 查看提交所带来的文件前后差别）
# git diff 更改前后工作树和暂存区的区别 git diff HEAD 工作树和上次提交之间的区别
# git checkout 切分支
# git checkout -b 创建并切换分支？
# cd (切换)  ../ （上一层）
# mkdir 新建
# 分支
# git branch 显示分支一览表 git branch -a 查看当前分支相关信息  git merge 合并分支
# 各个分支互不影响
# -切换回上一个分支
# Fast Forword   自己分支上合并 --no-ff 分支合到master
# 更改提交的操作
# git reset --hard
# git reflog 查看当前仓库的查看日志
# git amend 修改提交信息
# git rebase -i (+版本 例：HEAD~2 选定当前分支中包含最新提交在内的两个最新历史记录作为对象并打开)（把被合并的pick 改为fixup）
# 添加远程仓库
# git remote add origin +SSH
# git push -u origin master (将本地仓库推向线上仓库)
# git clone +SSH
# git pull origin