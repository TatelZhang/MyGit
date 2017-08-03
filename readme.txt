
git init 		  初始化目录为git工作区，创建版本库

git add <file>		  将文件从工作区放到暂存区

git commit -m 'msg'  	  将更改合并到分支，提交到版本库

git status		  查看git 版本库状态

git diff <file>		  查看未提交的文件修改情况

git log 		  查看git版本库版本信息

git log --pretty=online   忽略修改时间等纯净查看

git reset --hard <版本号> 返回到版本

git reflog		  查看版本修改历史

在工作区的操作需要使用 git add 将修改添加到暂存区，使用 commit 合并到分支

每一次add 意味着需要commit一次，在add之后修改文件需要再一次add


