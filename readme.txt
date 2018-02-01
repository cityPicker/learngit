Git is a distrubuted version control system.
Git is free software.

I am learning...

$ git init		//创建仓库
$ git add <file>	//添加到仓库
$ git commit -m "注释" 		//提交

$ git status		//查看仓库状态
$ git diff			//提交前查看difference

$ git log						//查看历史提交记录
$ git log --pretty=oneline		//查看历史提交记录精简版
$ git reset --hard HEAD			//还原到最新版本，HEAD表示最新版本
$ git reset --hard HEAD^		//回到最新版本的上一版本
$ git reset --hard HEAD^^		//回到最新版本的上一版本的上一个版本
$ git reset --hard HEAD~100		//回到倒数第100个版本
$ git reset --hard ecea			//会到版本号是ecea的版本
$ git reflog					//查看历史命令

creat a new branch is fast
zai dev 修改了本文件
又在master修改了